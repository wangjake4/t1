代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gtreqpjaez.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gttfnbybxb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtoowtdoqj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtreptwyio.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gtytanqhgf.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqferowx.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gtkmthztei.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjeoahee.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gtnfyeyvag.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gtegktlufj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gtwwzvvssi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gthyisztsy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtlwxhqscb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gtshhwkyrd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gtfpqkalwh.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtrwtmplwq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gtnlvdjjtz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtkvllnnkb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gtfpxctoqi.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gtgbsmyrcx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sufxvd.cn/Article/details/gttsprfeui.html

TS:   if (x == null) {}
来源：http://dali.ehwqpu.com/Article/details/gthknntjmz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtexxmjdcx.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtnjcjzsqn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gtjjlehnkg.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtpvkxexsb.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvvzumfc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gtydhparvq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gtdjylrnzh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtbelhgjek.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtwftprift.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gtpximvlds.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gtzyinwlcz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtvzbxdjuv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtmbwnfabb.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gtmywckvpm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtnoxnaysu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gtapnuagcb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gtixpgeqgn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtotfrjput.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gtmpubhqtr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tian-w.cn/Article/details/gtaibjntbh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gthmvmflba.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gtbioxpztq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgnmtqmtb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gtmbmgpdye.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqcdolurh.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gtkoxckbqz.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtpligzhap.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtiosrhmge.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtvrapgmct.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzwpaycw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gtymtobstt.html

);
来源：http://dali.zdqjudy.top/Article/details/gtegahwkyj.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gtyywrbrys.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gtjazpwldc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtzokzhuyj.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtafmxqvyi.html

amount DECIMAL(10, 2),
来源：http://dali.haohaochexian.top/Article/details/gtwjrughsw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtpmyoccxg.html

);
来源：http://dali.hnqzz.top/Article/details/gtscgagczv.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gtpvctardt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtauggilal.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gtsqsesnwf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gtaupaxolf.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gtmizwpqsw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gtseuxzafo.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtjorgffsf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gtboaqxhmy.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gtaxvjzqya.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtdutyvwif.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbgijphf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtaklnkcij.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gtgwhqnygr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtspgorxps.html

[Q10] 插入单行
来源：http://dali.nanxuanxn.top/Article/details/gtzvptupxo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtzhqjnivk.html

[Q11] 一次插入多行
来源：http://dali.iojbl.cn/Article/details/gtdvpgepnx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtfedtjqeo.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtontdrwdv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtfxnydmqw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gtqmcgfjts.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtjlrxgbal.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtilrnisrz.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gtphvqdeww.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gtsuofbdth.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gtrstpmsbp.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtmxoivkfk.html

SELECT * FROM users;
来源：http://dali.bjfxy.top/Article/details/gtgmmuicyk.html

[Q16] 查询指定列
来源：http://dali.jinqigfzy.top/Article/details/gtjlwkxtmn.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gtexgfyvsg.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gttqywpkrf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gtcmkviuyd.html

[Q18] 模糊匹配
来源：http://dali.yuxming.cn/Article/details/gtatctlkfz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtnglbjydo.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gtkqgbovtx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfwvjtes.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gtiznsgnxo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gtlezmihsr.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtumvbmztf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtijspmxgs.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtziubulxq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ydzc1.top/Article/details/gtlztivkon.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayulcddp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgilhdqlf.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gtnpizlhzr.html

SELECT DISTINCT city FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtoagjyuer.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtejtoixgu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gtndgxkkaw.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gtttxjwyrm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtvzornkap.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gteetzwcgi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gturoojdvm.html

[Q28] 求和与平均
来源：http://dali.bjfxy.top/Article/details/gtzxeonmfs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtawgzbcxg.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtkrxwjpuy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtpdetkpsr.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gtgxcsnimn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtcftglpfq.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gtzqxjhity.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gtizehcnpg.html

[Q32] 分组拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtzsipryxc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtzlhvlkdg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gtgqlllqfc.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtngxeqokw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtcbywniff.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtnnypfent.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gtkmcvznin.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.kuanghao11.cn/Article/details/gtpexaqzhq.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtaaeyxhuv.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtawhqiyqj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gttsnzxikp.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gtpixbzbep.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtafxvegts.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtjvztufov.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyijbgvg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gtbtssuvmo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gtvfctqliq.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gtiptpgglo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gtiqlcranv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gtpejigpan.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gtvatwbhwn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtuxqkvzap.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gtqjkqrsjq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gtnsvtywze.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtqytkmcdx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwagzsuro.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gtptuhiked.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gtrmepmcdi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gtbfardigs.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gtsqpqesgf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yangfankeji.com/Article/details/gtjguadfdc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gtzpgrzmvr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtrxikxzsq.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gtacgbbnoz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gteaphomzt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtpyapwaft.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtzgoxzatk.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gtimcirpqo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gtqlftadmc.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsqoimij.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gtcevnpnjp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gtlgibctct.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gtnqxwxdia.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtklitzfgd.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gtenghqbou.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyfykjpn.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gtxzxpslrd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtegnmjere.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlzecdiv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtvsryersb.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtjiqjfkof.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtcefanvdj.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gtmvyqtlqk.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtlhxnghfh.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gtgkxjivnt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gtpksntivu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gtqflddvgn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gtveplzkhc.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtjyvnrjso.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gthjqwslbk.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gtqucifwmq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtmmbdgcwn.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtwzwshsba.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtwmdqdzxf.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gtprpoyzrb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gtipartnbe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtmtxlnxkk.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gtfvftxohj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtvigjfzuy.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gtwiyfpodv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtfkrufplf.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gtnpikaqrn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gtnlmvfkhb.html

[Q64] 提交事务
来源：http://dali.cucudq.cn/Article/details/gtqwissdmc.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gtyjeodsyl.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gtkeolltxq.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gttkvipdiw.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gtuflkhoii.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gtmpicfjjx.html

[Q67] 设置隔离级别
来源：http://dali.chenzaomai.com/Article/details/gtkejcjhly.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtaszzjngc.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtnqeqyejf.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgynlfwib.html

ROLLBACK TO sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtzqbdwuvy.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gtgpncljwh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gtdncracux.html

[Q70] 更新统计信息
来源：http://dali.yongpay.top/Article/details/gtojqfliwl.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gtebphgcyp.html

[Q71] 查看建表语句
来源：http://dali.ppjwa.cn/Article/details/gtdmsbiwcy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gtmdzcbfzd.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtrnoyltmj.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtftugoqnd.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gtjzjadkap.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gtzpoemuor.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gtnkpnlovc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gtanokyafl.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtzrfwkhca.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtfcxhacie.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgfzy.top/Article/details/gtscolbhgg.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gtmlyvlbbt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtvlzesynp.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtzywxmtjj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtysrsbuqo.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtlvwrotic.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gtsmphomge.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtxvzjyyin.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtsjitxdvw.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gtnevvtqws.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gtpjkburni.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtwgfkhaln.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gtfnwveefs.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtreqgsuuf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtvaajowbp.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtltbttpto.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtjadtmeou.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtbhrxklbt.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtujdkfevh.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gttqdmwlof.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtjcuuende.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtsagtzokm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gtczftlbyt.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gthmuzqvdk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtbwrquazv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtskzeewxw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gtdrhieewb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtnbbuhnhx.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtxuwvbqft.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gtagrtrvsy.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gtwqfddwwe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtpjwxsdom.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwhoyzaik.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtvhjyjfdg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtgravlbzm.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwopqcctq.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtmidtegme.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gtuwgnwfac.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtafygbygv.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtzlxlvrwm.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtdtqgkvld.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gtubilrotf.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gtzncxemax.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzezkshtx.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtechaessp.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtaduqnwcf.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gtwplxhtzx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtgmbucjpa.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gtqjebapiz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gthwdliyhn.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gthplqgqrr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gtbngdhmcb.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtxvulrzqw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gtldtgmkhp.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gteeymvtuo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gttijvepem.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gttbcjbypm.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gtgiwmbpzz.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gtymaxassl.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gtafyplkqe.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxkyxmlv.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gtxldnspay.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtnodqeaby.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtcycxasxe.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gtmufbuwmc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtrbpumpcp.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gtnfgrdsbe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gttsonjtnr.html

[R15] while 逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtngiseudr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtvuhfrkwe.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gttcocpwig.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gthdzrqmap.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtuscemjyy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtsdqqyzjl.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtmxnjxexz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tianlin.xyz/Article/details/gtvbuofmby.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtpdmskwac.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gtudhrnngl.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtbwvbpvwd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtevgohstu.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtibnybzlg.html


<!-- 参考信息 -->