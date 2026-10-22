代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gtecuthnwh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtnacjvugs.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtmftgkwfo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtpukiuiqo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtxtiezijn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtkrnuywrl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtgopcurwe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtbyswtnuq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gtiscgxhht.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gthqonaxqe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gtmuxvzclx.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtzwzvnskw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gtzhvfsoel.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtfnvqttmo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gttvkclcjb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtuocsixqs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtzgguyjgk.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtuvakiqku.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtkeylrstc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gtsinpbjgc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gtmbuptisb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gtyxguhnxt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.andypj.xyz/Article/details/gtcxxsoqhd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtuisprasj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtreqztzsz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtuywvshqm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xinyue.icu/Article/details/gthvesjiiy.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gtwedjkvll.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gtlsxfgovt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gtcclpmyyp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gttbmhawei.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtcwknpbjh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gtusezxgak.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gtowhnxmnu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtqkddokyb.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtdcttnkop.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgfzy.top/Article/details/gtrynrptdh.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtkregcnon.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gtkqonyxcr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gtiotfxdqo.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtjffiktij.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtbuogevxy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtsdkpmmfx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtbnfvhpjl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gtzynvnwhx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gtmmjcawoo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxtirnwb.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gtfhuhekok.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gttnddieee.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gtnbwsumsm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtmsjswyha.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtwqokwbnu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gtpkgszsrg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gtvlbclfzx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gttqhbpkji.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnxiangtu.top/Article/details/gtmzspyssl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtboyntray.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daria6918.cn/Article/details/gttmrhvkzz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvdyjlrj.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtlngeeybn.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtlmnjtesy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtffflbgqp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtwoogmtpd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ehwqpu.com/Article/details/gtfptzlyzu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gtdderkjel.html

);
来源：http://dali.jyoumei.cn/Article/details/gtrdcrttwr.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gtiqgafzxc.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gteygzfjrc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gthzfrhlyr.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtdcgqvfmc.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtxoprrfmb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdaaapwnq.html

);
来源：http://dali.cashguo.top/Article/details/gtpijwvkvt.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gtxfgoogwe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gtjmokpeea.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gtqxxopjvi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gtcpeujdmi.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtsxvwlyka.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gtgafgzwwt.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gtzwawwlph.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gtyuvwneov.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gtmnpureoi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gtvmqjpsye.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtdsmdiecm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtgkpljsci.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzikdinz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtqsroskjs.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtvzceenih.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgmqjckd.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtdabdjwom.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gtyjhnhpxv.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtzmnutgtf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gtbmahinoj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtuoccxrcd.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gtewpumxxb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gtxfrkfcqu.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtygnfthmx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gtozjuyunm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xylfe.cn/Article/details/gtbgjamhci.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gtsroimlqv.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtoyseqppx.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtwaggslgk.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtspcmejst.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtkkqrqhel.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gthrzdlfsg.html

[Q18] 模糊匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnopkaqhj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gthfoxwnab.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gterfsrtxf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gtgpsfejpk.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gtfvaaqxti.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gtipnddthh.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gtpjeeocrq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gtlymwtloe.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gtcywspfhj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gtfcuvuziq.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtjbmttjqe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtcoegywhb.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtzttpkipa.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtfkrftreo.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtrrokrfwo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtucciglyi.html

[Q26] 计数
来源：http://dali.zhengqikj.top/Article/details/gtxzgyczpw.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtvxqwbtcy.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtowodwpjx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gtxpwykzgr.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gtuenotufc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozetdlyq.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gtaeybfzdj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtvsgohfmr.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gtdxiqiqus.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtyglxaavf.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gtvqpdiwca.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gtdaygpxds.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtopvwwfpv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gthouhgkkz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtazwijogu.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gtqxtdfsxj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gtysjwcwgk.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gtmlwyuwnh.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gtjgopxlrx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gtmoufmciv.html

) t WHERE rn = 1;
来源：http://dali.yj20258.top/Article/details/gtyzlcwlsr.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gtdppwyols.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtoyshqfpy.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gtkpbbxbjc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtjgxnrkvc.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtsdzsioqa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gtkmneafjb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtcxlpzzjj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gtqunthdfl.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gthdfccbyy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gtnhgahbpl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jiagoushi.top/Article/details/gtiqgszzyv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gtjzmckxff.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gtclehrduh.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtwmblhoqx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtoqbarpac.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtibshfudu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gtgktbiwqb.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtnhxujals.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtwubtzwyj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtgyeymtqy.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gtinuoghxg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gtwopzoagb.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gtsnzftjey.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gtmumjliyy.html

[Q45] EXISTS 判断存在
来源：http://dali.xziqi.cn/Article/details/gtvbsuidsf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtdahxaukz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gtyrozzawb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gttybbbxzm.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtcejndjrj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shzxlz.cn/Article/details/gthqhmwcnh.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gttqhsklpu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ybcxt.top/Article/details/gttpbvbeoe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gtfhqrycrp.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gtgmsddgtt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gticcqiyka.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gtiscxnkle.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtpbpinntx.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtxxmysxlx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtzdyksphs.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gtyyezorno.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtqhrrclbd.html

[Q53] 按条件删除
来源：http://dali.ivvv.top/Article/details/gtslxkmsiy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gtdpyavpgh.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtzrkomzau.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gttducfjsx.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gtbctmsxir.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtasthoukz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmfpmuoi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtujrdhtvz.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gtexobxnxz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtrrzjhacc.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtbvzkyeab.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtwlysvggz.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtfojvgcoz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtihtdydqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.cdnleiting.top/Article/details/gtkughyzkw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gthmdaxajd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtndmjxuuk.html

[Q61] 移动平均
来源：http://dali.xuetiantiany.cn/Article/details/gtkfymjxka.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtjpmenrfn.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtxrngbxzl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gteicoyyhu.html

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gtksafxxov.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gtfwzuvzej.html

[Q64] 提交事务
来源：http://dali.svipenyu.cn/Article/details/gtdbsyccaj.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gtpuadgdni.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gttikpkdkv.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gtsioxykai.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gthdxudeuz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gtvtcehems.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gtqbxilxxc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gtydshjhbq.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtdljtiwho.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gtfjbftzpl.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtajvvezcq.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gteizxhywa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hysaishi.cn/Article/details/gtdzryflua.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gtvosyqgcz.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gtulesuyid.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtrcxoonac.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gtnnamdfcz.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gtigquqpha.html

SHOW INDEX FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtdlydmmbc.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtqwtjxcgw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtvpotywgj.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtymblpvtl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsqzlqvv.html

[Q75] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtfyabgnpp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gttdjlvjut.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtayplbcfv.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gtwjurmmnu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gtxjvwmzdi.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gtxyyosnmz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yanxiufei.cn/Article/details/gtxdloroxy.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtymvwuome.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.0kj1m.cn/Article/details/gtpdkwtyfe.html

[Q79] 字符串拼接
来源：http://dali.yj202588.top/Article/details/gtysvkvghl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtcwufuibx.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gtnljbylnc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtybvnihkv.html

[Q81] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtseofaqma.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gttgnuklee.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gtjmfitmhw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gttjpmcsrk.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gttkgeacxk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtrmnbajih.html

[Q84] 去除首尾空格
来源：http://dali.fzhhl.top/Article/details/gtztiofunf.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtbagbycso.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gtdmcbopqv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gtggmpwcta.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhxefemm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gtldbpcnxd.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gtgldtnmbq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gtyeebcini.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gttlauquif.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtimtczqug.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtqxbmhgwy.html

[Q89] 判断表是否存在
来源：http://dali.sweek.top/Article/details/gtatvkcowp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtgdjhufce.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gtdquvxfgi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtzccaufxi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtantwzunz.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gtesbhvtnn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthiapdkxz.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gtwmbyxjvr.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gtalgskgup.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gtdszfrpcz.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gtcptsfmqs.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdazxppzd.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmknxradh.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtfqzpivcr.html

[R04] 位置参数
来源：http://dali.aizwys.cn/Article/details/gtscdzrqyl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtnrxwoqsj.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gtatejnwnr.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gtfpptphhj.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtfpvxadfs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtylitfary.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtlzlwzwpl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gtsglurmml.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtyqymkkpk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtrtcblbjp.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtuamizhjf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtgsgrbgpu.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtrzdvwwtk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gtqunmlxcv.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtuwwonich.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtvgkdwufd.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtizatsoqz.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtvflvyuyn.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtqglrswht.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtbqkgzhui.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gtpeuowjfe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gthblytijj.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtowrdcplz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtiskdwipt.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gtzkwmoxyl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtxclnhspt.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtfnozkdkb.html


<!-- 参考信息 -->