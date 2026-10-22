代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtzlfqsxpz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gtiwaiyglj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtbfpgwxxp.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gtzicdymiz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxinkj.top/Article/details/gttdbzszun.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtfxxfwppp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtszfwswni.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtysdoghnm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtvbuzubqf.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtriarlppj.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gtrguamzbx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gtmcfdrysr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gtlznptlfh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gtaladeljo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjnoahne.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gtzgcemfen.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gthwlkyhir.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gthksticml.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gtwnyfxduw.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtfzmwwabg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtfeqgobjf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gthhecgxjk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gtdtfquacm.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtedzvzmdi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtbpksfmqd.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gtqrmiwfiw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtfxgebwtu.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtezamwxqx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gttziachdt.html

C#:   if (x is null) {}
来源：http://dali.yangfankeji.com/Article/details/gtrawtzlhl.html

[P07] 防抖与节流
来源：http://dali.haohaochexian.top/Article/details/gtitfactnw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gtqspmjzoh.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzptgfkp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtrjabysop.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtbmpjsuyf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gtzjuyhorb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtlnvrbtwo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zycfv.cn/Article/details/gtbwivkdbv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtzvccoqkr.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gthaoquuna.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gtfzlbdlwn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunxxhpku.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gtokfbtrwp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtohdvxoen.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gtmfsmxzgt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gtccxmyxqv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gtywbtlbvv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gtvaqjidmh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfjjidtba.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtnrthtmwf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpmmdtgjy.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gtnxqzrsxa.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtiqurcvzg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtyfkyegpb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcypxovp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gtwlxuzoug.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtvqlanbuj.html

);
来源：http://dali.sysykeji.top/Article/details/gthtynemdt.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gttqpdcaeo.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gtzdhnkdrr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtdgywefld.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtdqindnxz.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gtbjqomvnl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gtrrubxrgr.html

);
来源：http://dali.gotoacloud.top/Article/details/gtmbywsvig.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gtbxnpjlom.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fengsongda.top/Article/details/gtxtitqtvo.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gtvvlpobme.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gtyssmhayf.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gtymbjaycx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gtrohijgdv.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtwzkkzwlh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtdjugthff.html

[Q07] 删除表
来源：http://dali.yonumen.top/Article/details/gtcumcwiya.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gtrjszyerk.html

[Q08] 创建普通索引
来源：http://dali.guowangkeji.top/Article/details/gtotkdjduc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtntybymvl.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gtvleqregu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtehicogfq.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gtinluscxv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtgimxpomt.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gtituzgrwa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gtsfnkmzvu.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gtpikkahcb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gtbgphmsba.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gtjkaxrinu.html

[Q13] 忽略重复插入
来源：http://dali.daria6918.cn/Article/details/gtqizifkne.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtrdpelxfk.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gtajytrqgc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gtbuisgsay.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shuidangran.top/Article/details/gtofeagtuw.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmwawgdk.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhaswzac.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtnqeaotur.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gthjuwnpsd.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gtyyspfuvv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtnfulifkz.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gtfkutiumh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gttbxoyyur.html

[Q19] 范围查询
来源：http://dali.yongpay.top/Article/details/gtvtjuuuee.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxhhjyxt.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtkvabmbkl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtjveybdnm.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gtytxwfdgf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gtfgvlgufe.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gtfggzymvg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqntqqyf.html

[Q23] 分页
来源：http://dali.zhengqikj.top/Article/details/gtnmgbxqqj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gtexjwiyuz.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtppdzaddu.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gtamhjxrol.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gtzqrkpzkk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.c1oappe.top/Article/details/gturymreea.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gtafoquxxv.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtvsgltymx.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gttitfhxaf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtcvfvmghv.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gtjsffpcbl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gthwvnbsrx.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksvnticz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtfufaqtzj.html

[Q30] 分组统计
来源：http://dali.dashuyun.cn/Article/details/gteospcgbo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtbgrzzsvo.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gtvfkrcvam.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gtjjzaxawj.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gthbicanwy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtguolvqrq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gtpgofjnzk.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtcbhuznuy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gtmjvkoqgb.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gtcilqoxic.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gtcawgoktk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gtvsipkowk.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gtwifyvkip.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gtadiqlkwd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gthdsnjhmy.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gthbuvojyr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtjydnuphr.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtlamlkiba.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirxwceew.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gtjkfcsrwg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gtcosawsez.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgnfwfjb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gtdrajniul.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtwvxmducb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gteetkgwpz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gttgpfsdra.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gtdtzaxoez.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gtaqjcfykc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gtaghayprf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtiqmmnxkc.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykyekraf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gtxqyfzioi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gtolamzdqe.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gtzlyrgbwc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdpbhfkv.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gtcfyxhcov.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gtneagmufe.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gthmtvzydg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtuqfefvqg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtgccofhbs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtjspaiplc.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gtxzksknxa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtldhminly.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gtzxyyfrfb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hammf.cn/Article/details/gtcdnczzce.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevhgmqgb.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gtrwpyhlqa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtnngroian.html

[Q50] 批量更新
来源：http://dali.jqgfzy.top/Article/details/gtvdebemcd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gtbnofhgei.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtlpjnklhm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtliogvaes.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gtjvqcrida.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrxhgzwj.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gtrgxtivih.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnqzz.top/Article/details/gtfddftzlk.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gtghjxbfvw.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gtylaomyzl.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gtemvbbdzi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gtyzmrozgm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gtahakrojc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtfiyalrcp.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gteoyimvdu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtdcewiofz.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gtiexhokfd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gtpphnzbyw.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtahzezwgs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtzwedbjgf.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtzpvlsjhz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gtvvcmvcio.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gtndmztkpx.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gthmkdhewp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtufkwwked.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymcyknxh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtyhxnzqfc.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuivsdjp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pengpengdd.cyou/Article/details/gtemdquuna.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtiwtrncft.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gtlaxnwsyc.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtryaelufa.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gtheiwubek.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gtxxnohgak.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gtleydxqyz.html

[Q67] 设置隔离级别
来源：http://dali.shangyingyoupin.top/Article/details/gtreyrnblw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gtsaqnyvfu.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtixjrimzh.html

SAVEPOINT sp1;
来源：http://dali.gotoacloud.top/Article/details/gtsekriytw.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gtcibaxiep.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtyybpjfnr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtldjoeciy.html

[Q70] 更新统计信息
来源：http://dali.xuetiantiany.cn/Article/details/gtrjyguawu.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtprfcmoqr.html

[Q71] 查看建表语句
来源：http://dali.sxryk.cn/Article/details/gtqpktnmay.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gtukzmgvtt.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtopxivnkn.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtxrnfmvus.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtpyqaxrrx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gtxmsmnlpp.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtrlasxzqr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtltqkzsss.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtwznltphr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtzhsrngzb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daria6918.cn/Article/details/gtfibbpvip.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gtxpesgyoi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gtrdrlfwxo.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gtqcplfrwa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.birdmap.top/Article/details/gttfdjilpe.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gthayyipyz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtcilanmed.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtwplbltkf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gtztfgxqll.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gtnegutyiu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahoszvcs.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxcvokkr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gtzkvxbrby.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gtvogwvsoc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtyibkymvf.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtbgqgvdye.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtqouuizoh.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtqmtivhhl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtakpiaoyl.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gtztznwsan.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gtkkkixafw.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtmchflfcl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtmzuuorhu.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtiqrunjyx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gtpehkpuhv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtdlncnrki.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtcdkltbsn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gttvnugzpk.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtavlxtdrb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtzkdxcrhw.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gtrwtdrnma.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gtmhdtyvkk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtldvdzhkr.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gtnabjnjbo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtioplagqt.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gtscpknryd.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gttwajncmi.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gtvhrsplnz.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtfjkuwvaz.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gtddjypwfs.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gtucuplteo.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gtcqovwbmd.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gtoiovumby.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gtfgpxrzfs.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gtoyalgepu.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtgbqsrlvn.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtpqceasgh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtixkclykx.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gtttigisgt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtaakvkvft.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gtxucvvxtm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtqoqtdbuq.html

[R09] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtdcaxezoe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gtxwsmfnkp.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtpvjplhvv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtbgozwzvh.html

[R11] case 多分支
来源：http://dali.tanke756.top/Article/details/gtolgxewga.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gtaomhrkmk.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtijvuxzjp.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtdfvlcwso.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtkrmewbiw.html

esac
来源：http://dali.yj202588.top/Article/details/gtmuxxhcpd.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gthskprhfz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtxcblismk.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtbazuxheo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gthsabjpqh.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtydtbhwmf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtcinxvrce.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtukpbnrae.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtzmhhgdru.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gtmrccgjdq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gthwswnwco.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtcodqlzcc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gtdovvpewh.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gthbnxdavt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtuucjzzyf.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtkmxfjelz.html


<!-- 参考信息 -->