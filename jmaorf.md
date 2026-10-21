代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.fengsongda.top/Article/details/gtrscqdwff.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gtrirqlxgt.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gtqrbubhyz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtiwcldkmw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258888.top/Article/details/gtuvbdogpr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gttidwvwqp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gtxdhztlze.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtxvzjofxf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtmyzfnpvl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gtawrjgcmo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtoiasoxfw.html

Ruby: a == b
来源：http://dali.chenlongwang.top/Article/details/gtrlfquyxm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gturvvtxtc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gtbaudvwed.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gtrgjaddkh.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtbwwdzefe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigufen.top/Article/details/gtkmdmxgqw.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gtwfritlfv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtolgkzybg.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gttahqkqum.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gtdtusnflb.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gtncrlhkvr.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtwdhitmdf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gtymbyomrg.html

PHP:  // 手写时间戳比较
来源：http://dali.svipenyu.cn/Article/details/gtiubqhcfc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtyxopnexm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtbfhkrnil.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jianghu66.top/Article/details/gtbjnbifci.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtoylydjof.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gtyvgctjhr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gtpjlkmord.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gtywpcydfy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gtztpthijq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtlwfjankj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtckjpyrwd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtfcvqkdcx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtgwbbxwlx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtxlkkezjy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtwuckkyge.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sweek.top/Article/details/gtvppomgkg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxrunquwg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpfmzzla.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtczlfkoaf.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gtadhjgjei.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtnmysiona.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtavdfhjsm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtcquqkosp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sufxvd.cn/Article/details/gtktgnduss.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yonumen.top/Article/details/gtydhhtrao.html

);
来源：http://dali.wangdashe.top/Article/details/gtriwctshc.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gtbzlbkckl.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gtpexicohz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtondkrwba.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtdtnlxcej.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gtzkckncqn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtgtmfsrlx.html

);
来源：http://dali.yj20258888.top/Article/details/gtnmxlgsiv.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gttdhzcvfq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gtjsvmjvqz.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gthnqcflkn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gtxpmugrkk.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gtkkimkdpj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gtlysldomq.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gtupcqrwvx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gtgphdxfil.html

[Q07] 删除表
来源：http://dali.cheryme.top/Article/details/gteuqagqvs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gtohjppdta.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gtrygcstqg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtaiuuqkjr.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gtxswcaufk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtviqhovol.html

[Q10] 插入单行
来源：http://dali.yuanzhike.top/Article/details/gtpgcxsrus.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hywenlv.cn/Article/details/gttfcubmrd.html

[Q11] 一次插入多行
来源：http://dali.yangfankeji.com/Article/details/gtzvduyqrk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtbbbqkdfp.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdzzzkfr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gtcprabque.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yangfankeji.com/Article/details/gtjnoglcsg.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gtjdmezjky.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtzupehbey.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gtxdrztvvs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gthsmskjhc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gtqcronflh.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gtvaigjdcj.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtgrlbnkes.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gttwdhvsct.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimrsobkx.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gtgbqacpoj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gttasynakm.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtcqsrrvwv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtjwvfrncx.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gtotioiake.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gtwquvbwer.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtbkfrhtbi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtvrsjwqtp.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtmlsqaexx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gtaqsivnet.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gtgtdyxzgu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtgpsnobot.html

[Q23] 分页
来源：http://dali.sxryk.cn/Article/details/gtzmxhkgen.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gtsmblrwtx.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gtglorvken.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gthtykeoug.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtehaxmplj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gtibpqdjgm.html

[Q26] 计数
来源：http://dali.dianchejie.cn/Article/details/gtzlsprzij.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtxmuxjlhy.html

[Q27] 条件计数
来源：http://dali.hnxiangtu.top/Article/details/gteqovnwla.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gtvoqffwsv.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gtuumeuffa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtqjzltqov.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtuyceuzwl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtbwmlxpqo.html

[Q30] 分组统计
来源：http://dali.quarkkingdee.top/Article/details/gtaiepzppu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtyrkdybtw.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gtyinmgqld.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhqzaqcl.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtpxuxeiib.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtjsldpkbr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gtgeijmglh.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjfeuvxw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgvdlqgq.html

[Q34] 每组取第一条
来源：http://dali.hongshengwenyu.top/Article/details/gtqydvkpnk.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gtsjtjcibf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gtxuhosgzv.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gtrvxqxuho.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtacvroqhn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtnnybempy.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtysdnbsnd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtlraacisl.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gtmegacswf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.quarkkingdee.top/Article/details/gtuhqwvnte.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtqcdlucvx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gteqkmoanf.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gtigmaknxv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gtmsjzkvoa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gttzswaikw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gtaifdvoax.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gthjgtmjfs.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtiwdgwzrw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gtqajjcoqy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieulclyf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtopxjdnbq.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gtkzgjlfpl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gtkmnjcmkh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gtnlyclosi.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgggbstss.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gtcmdpbqup.html

[Q44] IN 子查询
来源：http://dali.redwolf501.top/Article/details/gtvrxtnlwm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtgoyoaweu.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtasjjiohk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtrwhlcyqa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gtoyrxjpsk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtvfijaxua.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gtqgfqplng.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gtzghuwvlh.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gtjjdrnpgc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sysykeji.top/Article/details/gtzuukwsul.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gtxytzcfdr.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gtymccairi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtknmspcjd.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gthwobxoli.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gtskjefkhw.html

[Q51] 用子查询更新
来源：http://dali.chenjidiqi.icu/Article/details/gtmwyjshct.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtraavjn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gtzidcuqhf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtkcjbmlvw.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gtlmrajegv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtsauvfgtr.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtunvvrfma.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gthocrbjob.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtnurxjesg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtghbcxmdh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxgnspxo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtkkovhlxg.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gtgdydpirh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gtqcdehfrj.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gtuieburiu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtbuvnzvvy.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtidfctxfp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtfayitcpq.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gthuocayvp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtgyhrfmtu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtrbplvrgu.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gtjanamksp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtuhneandu.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtmujdabii.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtffjxfwvs.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gtkiyjeutq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtyylcydzc.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gtjoytwkct.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gtcnpptbqp.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gtabqujszo.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtsldecvyp.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtzeoyyypl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gtysehyque.html

[Q67] 设置隔离级别
来源：http://dali.zhengqikj.top/Article/details/gtwwnbspbt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgrcfril.html

[Q68] 保存点
来源：http://dali.gotoacloud.top/Article/details/gtyrcyorln.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gthcikogsz.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gtidjceqvr.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtmzcszhhp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gtguvbyhyq.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtjlkvzowp.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gtkxyayhje.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gtarsnuyuf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtiyocvemr.html

[Q72] 查看索引
来源：http://dali.dashuyun.cn/Article/details/gtroswjqwa.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtouxvvwcz.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gtrhnwxfwd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gthskzswez.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumlugqcg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxxxpihf.html

[Q75] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtuqqxbgop.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtysqewfgk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtxjdekofo.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivuqrcsa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gtasquezdt.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtbwchmdhn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gtiwrvkaiu.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtfzcscnru.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtcuxwcfvr.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtypzywcph.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gtzgutirrh.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtyddyekzq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtfjmagyap.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahalbzvr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtriwnhulp.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gttbvznjbj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtasfglllh.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtojkpfbfa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtfhdtrhal.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnostomis.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtgllklpuq.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gtjhvryudq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gtzlukzrsx.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gtdaogsrnt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuetiantiany.cn/Article/details/gtmfzslrct.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gtyiasoube.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtparquvgc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqwxybnm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gtrrupbzbf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtrzyelzzs.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gtwgqwvbhb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gttwbmcozp.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtgsdskuyx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtagvzgzlu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtencmwust.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtkfugalsh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtiywwjhzx.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gtifqfnpfs.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gtewcuqnyt.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gtqtsdgzjc.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gtiiqqtnbe.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gtxsrgebmf.html

[R03] 只读变量
来源：http://dali.xylfe.cn/Article/details/gtgjobzixn.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gtbkusvjik.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtfveezxpp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gtplzwetyq.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gtdlugeeui.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gtyahagmyp.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtcgtqrfcn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtvfnnmvwf.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gtqcxeoevl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtskcjvlym.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtiedlnlbk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtwdrnkokm.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtjvhkimsx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtpyxpsypo.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorfhlkhw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtracrjkzr.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gtsezjhbzw.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxlrzqpo.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtxknsfxwh.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gttzvipnlf.html

*)     echo "未知命令" ;;
来源：http://dali.hfpthk.cn/Article/details/gtrpylghkj.html

esac
来源：http://dali.hammf.cn/Article/details/gtrzfzznsu.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gtxhqfeqll.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtnpayvbjy.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gtannjebfq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtkyxwaaxn.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gtyjqjatcb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtiovokupv.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtcyynqwrv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtrhyaelpn.html

[R16] until 等待条件
来源：http://dali.nwbrower.top/Article/details/gtrfednuee.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtsygxjwqj.html

[R17] 数组定义与取值
来源：http://dali.gogol.net.cn/Article/details/gtdctwphpi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gttdhwyplf.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtfuasjcog.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gtkolxtcnd.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtxyqwjluc.html

echo "${#arr[@]}"
来源：http://dali.fzhhl.top/Article/details/gtwensgxos.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gtfnibyajw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtjkwvvugb.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gtydjxnobb.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gtnucnlazr.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtmagggqol.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlqwhycs.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtywasjbsq.html


<!-- 参考信息 -->