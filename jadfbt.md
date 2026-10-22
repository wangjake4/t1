代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanbqeddx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtuwiwzsdf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gteagimmjd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtklhnqizn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtuhtvkxvj.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gtebizwfrh.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtnbffpfgi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtfnfqdvhv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jianghu66.top/Article/details/gtlcfjupyv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtdicmgikq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gtasmjvdrd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gtyklejkjt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gthxglopow.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gtxsdjuctf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtcwklrtpg.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtgjwexgyd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtingexece.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gtfjpyhabd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnofzgmp.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtqeensiwa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gtstblhbcx.html

TS:   if (x == null) {}
来源：http://dali.yvedp.cn/Article/details/gtyfvmhbbj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtfnaiuvwz.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gtyzrkniep.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlcduemm.html

C#:   if (x is null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtujuypmuo.html

[P07] 防抖与节流
来源：http://dali.aizwys.cn/Article/details/gtpwemrqxo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzoqtutd.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gtrbxfafnf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtxjaefqfn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtvfuailmr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuxming.cn/Article/details/gtxdcyhfsg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gtpaxovxjd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtlnmilkhr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknfrbgpi.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqbswncb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gtgdqxnitb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqcvbtgt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gtjdboonrc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtzibvmhtq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gtgpuynkbn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtwskxrtqn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtrnhcwkjj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gtehfrfquf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtoibovnsr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhckasta.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtahgkckpd.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gtwlddfvuo.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavjlrlot.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gttkylchdp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gtsnzdikxx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gtddergmxe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gtdpuwmerh.html

);
来源：http://dali.yj20258888.top/Article/details/gtkmnsdzgx.html

[Q02] 创建带外键的表
来源：http://dali.snrcjt.cn/Article/details/gtvmfrcuxq.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gtqrvbrbcq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtgrtwqhnw.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtsetultvp.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gtwevhwzjf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gttdhmpzuj.html

);
来源：http://dali.9152youxi.cn/Article/details/gtgzzjszyz.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtupzwlqcv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtkeojdsog.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gtwehwmrrn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gtdzsmpbru.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gtufwocnhk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibprqoav.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gtbmyzintz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gtfwvjhqvl.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtvyohqcfu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gtsdyxrzyp.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gtsphulzuq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtcgxaxfjx.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtlnsgrasy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtpbpudqzr.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gtrpzyswco.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtmapopmmp.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gtlppdavit.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtpxzjgzew.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gtfdrhokks.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtqvhdhswy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gtbndxnpxv.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gtjtdiyoow.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtdapqrmkt.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtdnybevvt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtckiuziou.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtswuohark.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtoybxaliy.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gtrocmvovq.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjlpaioy.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtjqxcnwqv.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtzqrlzxvs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gtafomvzlw.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gthseoguqr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtjztvunxx.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gtrzjdayue.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtjfkvouwp.html

[Q20] IN 列表
来源：http://dali.jyoumei.cn/Article/details/gthbqesgwe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtdvuffmgo.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gtqioebslm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuyohqib.html

[Q22] 排序
来源：http://dali.sxryk.cn/Article/details/gtaryvhudh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtwosntqdl.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gtozfecwdh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gtdrqsrlqo.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gteqinkwwz.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtwzdutkmf.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtbicvsnds.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gtmpnmsovu.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gtulomcyky.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtegtlnlqk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gtugjrjsco.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtakcnzpul.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gttvrcjegs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtjxuogdpg.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gtawypqyic.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.birdmap.top/Article/details/gtbjlbhvry.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gtfffkkbuc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtaqfjzwzg.html

[Q31] 分组后过滤
来源：http://dali.iojbl.cn/Article/details/gtctetdudw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gtaydgyccm.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtfyhydfln.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtvvuemmfp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gtsxrvmojf.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gtixvliojw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtjyoljwpz.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtktfhakfl.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtyjvxjsnj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gtsyycvrac.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gtrwhbyxcf.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gthhftmiwx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtibbavpak.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtglyjeblw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtzkrctvhl.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtrpwbrqkl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cucudq.cn/Article/details/gtnjstfukz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gtobwnistp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gtdsoebmgh.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gttxwatyks.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gtsxazjepw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ivvv.top/Article/details/gtnrzfisqh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gtlnhkyxzf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtqcnqbjsa.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gtkbesqqhi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gtjvtmiwvt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtgqyxqpwt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aibaodan.cn/Article/details/gtlmpefvik.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtahndiujj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gttkwtuvzh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtacfkvkof.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gtivzmouyc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuanzx.com/Article/details/gtzfubptcj.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtsywlhrtp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gtrazmpwjy.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gtlrsbkejf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtslrdceeu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gtwkcctdep.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtuyobmdvp.html

[Q47] 与平均值比较
来源：http://dali.gaohongyu789.top/Article/details/gttwfbihca.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtnmskcgbt.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtahlxjstj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gtorhfqfot.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yangfankeji.com/Article/details/gtqoekrwfr.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gtzcscepjb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtkrsnjxjq.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gtevkvqwpd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gtzeyupqiw.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gtbsrttchc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gtdhriiojc.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtewklavxg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtdyahueah.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gtdncbjlmh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtgrlqswwn.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gtjeillthm.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtrvqedyan.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gtcobujqtt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gtlcxigdtm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gtrfutbaob.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtjhpnjrel.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gtqipjhxrk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtlovlukgf.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gthenvrjie.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtgvipzojt.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtalkdpfxy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gthsmvhzye.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtkdhegoio.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtiaxsznqb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtlbiqnjkb.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gtvtvatmgg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtawkulwsm.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gthpjqrizz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtrfiudhxb.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtxhpzfaje.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gtlqjfaxqv.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gtfguztstw.html

COMMIT;
来源：http://dali.ehwqpu.com/Article/details/gttqgtppkk.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gtjksoqnnf.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gtkzzodxip.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtgdkfivqj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtyeifccmv.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gtngktegwc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gttmlnlfpv.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gthhmpzlyd.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gtghqzfkwx.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gttwvmgqbd.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtwdrobyne.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtwimtbzpq.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtadeeajsj.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gtzuuxdtsw.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gtcbeiwxpj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gteiypmnnj.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gtvugjcsig.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtznzorrqr.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdhvocmn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gtewnqodzo.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaydyiqa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gtsynsutck.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtgtgyafhl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtwsejmufr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gtgdkcpdgv.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtqwbqugye.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gtvsecsaiz.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtdpvhnnrj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gtpioxogsq.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtukqedypl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gtqodngdnd.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrclfser.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gtywrsugea.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gtqzrmxwfc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtvazcamub.html

[Q81] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtemdurlou.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtdzkvketc.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtwmhfgmik.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtvfwgurvz.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtudnmffxf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtgamtqoue.html

[Q84] 去除首尾空格
来源：http://dali.yueranfly.top/Article/details/gtbmfsxfbp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtfozcqrii.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtygyhgnbw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtwcztgtgx.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtwtnmbdzf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gtxcctaxga.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtbqnmqlbd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gttzytakpy.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtwzfhhgok.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.mhx1999.top/Article/details/gtojppktxf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gtclclbmds.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gtmqiujpvb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gtpotwodfw.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtihpcgica.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gtlxryeqqy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmhbsbuvq.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbznogbpn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjkfitbjg.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gtlaomaznl.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gtvofsmuhf.html

set -euo pipefail
来源：http://dali.fengsongda.top/Article/details/gtwdzandei.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxanneew.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gtatwcgbxz.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gtrjrwcpso.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gtghkvrytg.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gthznekzjz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtosvivwzr.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gtjjmpcgjg.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gtbpoxpdzm.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gtgbkhnsll.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtoekaeanx.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gtdgkjdiwp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtsnpqshwt.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtsmmdawlf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gtttyuyfkj.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtqlypoxdl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gtjmpefxoh.html

[R10] 正则匹配
来源：http://dali.aibaodan.cn/Article/details/gtlsdttrmr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gtmmgdbgfx.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gttkposrbf.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtmnsjxyel.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtzbtlwrvh.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gtopuqhcdy.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtcvkzvcat.html

esac
来源：http://dali.shuidangran.top/Article/details/gtkltvjehp.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsrfvpkc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gtkhkdrhbu.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtiizzevoq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtgjjgjxwj.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtwwlcsktg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtaxdwbfxz.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtiahyblov.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gtbjdononi.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtnfjhlvxs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtpmmawyas.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gtudxojokc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hywenlv.cn/Article/details/gtqxosdchs.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtstpnkqji.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtpaojylgo.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtmacbitix.html

echo "${#arr[@]}"
来源：http://dali.meibo888.top/Article/details/gtarizzofs.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtitmbfjrg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gthlmmnmyc.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtikheolgh.html


<!-- 参考信息 -->