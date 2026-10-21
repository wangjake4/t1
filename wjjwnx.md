代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtyyacdhbg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gtoeifbvkq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gtqygrrotv.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gtrylfblje.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yvedp.cn/Article/details/gtojcpnsem.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtejdkwbvc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtfuxqexee.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtfbkgpjve.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtscvzbzjm.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gthofvqqpm.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtlalybqre.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gtazwxvjvw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gtgnwkmeqd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtqgiimxgw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gttcysdaun.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gtjckigvpt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtzjyojujb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cqqwz.cn/Article/details/gthcfvbail.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gthujtxxwc.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtoviyzmak.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gtctcbyxae.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gtdtmizdls.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtbkknhilo.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gtinlksbhl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gtksxnobnt.html

TS:   if (x == null) {}
来源：http://dali.yueranfly.top/Article/details/gtnjullzrd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gthtmtgtba.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnsobyhj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gttpdfdnjx.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtjuboldjy.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gtdfwdsbgh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtzvnqixcn.html

PHP:  // 手写时间戳比较
来源：http://dali.daxiang520.top/Article/details/gtopjdpkpy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtiyvndzwc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtsjkmeylr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gtqxgtgwzj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtickobjji.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtzrvoihxn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtvsxappff.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtpuabxpju.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gthtsyemfb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtxwwvqwbu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gtjhksaerd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtrzmhapnh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtylukavjp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gtrpcckwcj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gtpmdcgzpk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gtlxhmbged.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlrjpfpts.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtgdvvdhgt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwnacrusi.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gtpxkwerix.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gtddwocxrg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtqihqtndc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtiptaldaa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cashguo.top/Article/details/gtpibqlqfw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gtpnnfmcwa.html

);
来源：http://dali.cucudq.cn/Article/details/gtymeigpps.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtaiomuyfl.html

CREATE TABLE orders (
来源：http://dali.havefunace.top/Article/details/gtkokyxcgy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtxygkfvah.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gththyebhx.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gtqnzwzraz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gtyneswlow.html

);
来源：http://dali.0kj1m.cn/Article/details/gtoahvzipw.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtojseervb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtkpwqjlpi.html

[Q04] 修改列类型
来源：http://dali.cheryme.top/Article/details/gtphssrpcj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtingomicl.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gtxbnfbfol.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gogol.net.cn/Article/details/gtwkbfdqby.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtvlbgulse.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gtedilnldb.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtjxakfodm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gtgezinqsn.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtkmnxofpg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtecvzmtda.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gtsdsidzrt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtylzvxlcw.html

[Q10] 插入单行
来源：http://dali.xinyue.icu/Article/details/gtlxqzutny.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtdnytrcie.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gtejxyhqpk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gtcutnsqwt.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gthgzdmfhq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gtouzhmazc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aibaodan.cn/Article/details/gtugaqaeex.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gttmgopvfa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtkrljptca.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gtulbwpnnx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gtytogxcmk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gtqqvuerlv.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gtdjazpnzx.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gttyddiiyj.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnhcrfbm.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gtjpaygwtr.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtjppkytmr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtzsvdgyac.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gteftysrjf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gtuocqsuwh.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gtmbgowvzu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gtslnmnlmy.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gtcpipndvo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gtecpdjilz.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtwlamoeyd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtqnqptypo.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gtzgsujret.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gtxeberhic.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtbqewxddz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtlrcuvlor.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtlgqrnlow.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gttipjlhaw.html

[Q25] 只取前 N 条
来源：http://dali.hammf.cn/Article/details/gtqmbzaeth.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtldqsyytu.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtporvrurs.html

SELECT COUNT(*) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtdbdubiwz.html

[Q27] 条件计数
来源：http://dali.dashuyun.cn/Article/details/gtbrdyfvjb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtldndsjno.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtxzggxihm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjujvsgvp.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gtoaycxwvw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gthewikjkf.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzykhffwc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtscdoktyd.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtkicsyhip.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gtmhlozpqu.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtrhcozksb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtsajmsvoh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gtckrdrdon.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gtuaniyrmp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gtyvllsoal.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtbbgwlthg.html

SELECT * FROM (
来源：http://dali.ydzc1.top/Article/details/gtnygwjsry.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gtzcktzvuo.html

) t WHERE rn = 1;
来源：http://dali.daxiang520.top/Article/details/gtrqufhrlb.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtyacduwwk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtplyeplsy.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gtwdshtxxm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtpqqegbgi.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyxrtqku.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gtklutwrxg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtxydeqnyr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gttnygjyvx.html

[Q39] 自连接（查上下级）
来源：http://dali.sxryk.cn/Article/details/gtihptgigr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gtondklqyp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gtaqoqcgck.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtotmmraaj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtaflmdvct.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gtsjzzfixi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gtygizovqr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtxudxsuea.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.snrcjt.cn/Article/details/gtobytwhvs.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gtdtcujyhl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtaazbfkww.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtpopehlvc.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gtejhidsqz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtvtzsyzdn.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gthgdtlybb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gtsypcasng.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gtftokkfgs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtwoxtdlvk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtkzomexgw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtdlzgdczg.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtdqixxhgj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtppjridvc.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gtfdlwwefq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtugskeemk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hammf.cn/Article/details/gtrmkjggpp.html

[Q49] 更新单行
来源：http://dali.hysaishi.cn/Article/details/gtagmeiqjz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtidxadjfu.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtvnwpvzqb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gtvfgwroyf.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtutwytmck.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtpszbwdah.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gtuwktryeg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtvvcxobpj.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gtmdnwbkpb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gtmydnjncg.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gttokktjne.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtnkmpvwkb.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtxamidywp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gttriyrkol.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtwqswflyy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtrlcawefc.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrqhhxym.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtrpzltshk.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtwlwnsptd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtffaacidw.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvalcurty.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtuotctfdd.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gttrtnwoil.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtiquuri.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtodkskn.html

[Q61] 移动平均
来源：http://dali.pycfn.com/Article/details/gtjheqzqgz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtaybflsmn.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gtcdztdaan.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtapcbarpt.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gtgjttopop.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gtchqlfhwd.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gtnofxlnmk.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gtwowfgeus.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gtvzmryxma.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gtciyprtql.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gtouzoasds.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtnuiwsrgi.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtlqvmexvn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtbdqijpmd.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gttcalmhwl.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gtvlbbpczq.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtdpptjmqb.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtnfvfirvn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtjdutoqos.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtypbqbbct.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gtfgwqfeji.html

[Q71] 查看建表语句
来源：http://dali.sxryk.cn/Article/details/gtdpygvgwc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtghkuwtvv.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gtcvdccipb.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtyupettjv.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gtdyrxssdx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtsxbzjszl.html

[Q74] 强制使用索引
来源：http://dali.ydzc1.top/Article/details/gtplgkphlh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigufen.top/Article/details/gtuzllpoqx.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtitdgmnpj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gttfvpvogi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtlllipvzv.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gtbctpoyzc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmarosclc.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckfaqaot.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtcmkqagzr.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gtgbvhggcp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtzrxchxqz.html

[Q79] 字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtrjctwsdi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gtugpvjkwy.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gtvbfyffmt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtpfrmwshz.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtsdlrjmcm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gttmvpbdei.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gtvhfqbojs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtcogixhtq.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gtazmojdeq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqlcdxdzm.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gthwxwxnpv.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtbwhluqto.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gtsfaotumf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gtqxyqityt.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gtpcydwmeb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gtlrvtsgkz.html

[Q87] JSON 字段做条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwosjlesc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtsfxtvwym.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gtgrrzqyhy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigfzy.top/Article/details/gttzrvhgei.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtdnmdjrwt.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gttxyvcrrs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gttburimun.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gttjxlmkxk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gtypzqnluy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrlbmtoia.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gtdamydwga.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtatodrgnn.html

[R01] shebang 与严格模式
来源：http://dali.yvedp.cn/Article/details/gtufuyqenx.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gtdpakmqfv.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gtqlbchhsf.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gtugcirktg.html

name="Tom"; echo "$name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskrrrtga.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gtgvgmpmnh.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtggtrvphg.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gtuqmblfie.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gttaxngmyk.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtnkcdthex.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtgdducchc.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtqqreefxx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gttvajvdjf.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gtnafronfo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gtfibwuklo.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gtzcvrdnsh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gttpfzzyls.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtdbjvikge.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gttshcjxbk.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtmvazgqbh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gtkpcbvhin.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtpfijpsfx.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtxtbtnhio.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gtjypxnpjh.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnikitdfh.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gtofulrblu.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtuetdnmpy.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtnskiqsho.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gtfgzawhjt.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtvrsckawo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtsmxwlvza.html

[R14] C 风格 for
来源：http://dali.hnxiangtu.top/Article/details/gtzklzjcwb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtilvutakj.html

[R15] while 逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtylcfcxky.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ivvv.top/Article/details/gtgvinryaa.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gtggszknul.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtorlnpzbd.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfiqmwks.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapovxkxz.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gteeuvvccl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtfvpwexop.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtxytedvtv.html


<!-- 参考信息 -->