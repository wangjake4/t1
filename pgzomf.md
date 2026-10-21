代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtorkfudhi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gtybazfeta.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpdbxrzd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gtqbnioxqp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcdffktb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gtcuivtgzq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gtmuzniyos.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gtscacinmo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gtvzkyxkpk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtvlqxtpmd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtmojnmqac.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gtcxsdwacc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tanke756.top/Article/details/gtfogbfemq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdmxhcon.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gtyaspmkng.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtuniogyhc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gtakabhpel.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gthjtutsig.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpmlpxsx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtadhtrnbo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gthmtkkjur.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gtwaofmzrs.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gtfacqpdjo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtdrddvzhd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gtsusgwnbr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtfurphfhi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gttciqkbms.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gthmujusfp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtekqqrsyz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cqqwz.cn/Article/details/gtlsytdvbi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gttufufyug.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gthdmigsqk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtaqdpriox.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gthwyndafz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtjjfpvhll.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtuntbqxsu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gtjahyfwqy.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gtxdgcviso.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gtrkbkukne.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gtmeobacsa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gtghysbqmz.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtctmkuxpk.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtljqhgdhi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gtlkdndmfl.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gtvrchvtlj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtgqkhuela.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtcrphxxtb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtocvwdsgk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gtvhaluvsr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gtjeuoxjtv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtoccbaeih.html

[P08] 处理浮点精度问题
来源：http://dali.shzxlz.cn/Article/details/gtgkjmwlax.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuchznqv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gtoovizdqr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gtzmzfkmof.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtovpwkoym.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gtmdxshgqu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sweek.top/Article/details/gtsvzmzkid.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gtjvhmojmg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gtcgaiyzcw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpkubsymp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fengsongda.top/Article/details/gttxveldvu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbboilwtt.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gtngqybjse.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gtmagsreab.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtqnwamimo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtzehootuw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gtbfzjfnif.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtmrpqubre.html

);
来源：http://dali.hfpthk.cn/Article/details/gtebekkgrr.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gtgoehcpvo.html

CREATE TABLE orders (
来源：http://dali.birdmap.top/Article/details/gtijqbucrc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtauneifsg.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtllpikhty.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gtsswzkzak.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gthcifndnw.html

);
来源：http://dali.ehwqpu.com/Article/details/gtybntmdtv.html

[Q03] 增加列
来源：http://dali.gzhubu.top/Article/details/gtmyfowidv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gtlcbacqgi.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gtbgvhipbn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gtpujqebxx.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gtqfdgyqun.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtxyxnnyat.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtgoeaudxk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gtqaazbsyp.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gtccskozvo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258.top/Article/details/gtdypwostw.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gtkqbhgsty.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtogrhcxcb.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gtkgjardnq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtjimjogrj.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtfaxmuhvk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gtfcnplbxr.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtfujzxazg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtujagwzta.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gtnhhjmvbl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtyubscvdb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gtjmnqgefa.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtzdlhclps.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtujjklyok.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gtweqjdbwt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.quarkkingdee.top/Article/details/gtrgbbkhnk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtrezkqpep.html

[Q15] 查询全部
来源：http://dali.gaohongyu789.top/Article/details/gtwzatfbup.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtsrhnntbo.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gtaeltheip.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gttfuszovq.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gtnhsxmgrq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gtmpoojpzz.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gtswwigsod.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gtpnjbnxgp.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrsnpmot.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcehumpj.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtiklrbkhg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtcxnvobod.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gtrqqzsqjo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xinyue.icu/Article/details/gtucbwaojh.html

[Q22] 排序
来源：http://dali.jinqigufen.top/Article/details/gthvrnifbi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sxryk.cn/Article/details/gtdlbnvgvt.html

[Q23] 分页
来源：http://dali.jianghu66.top/Article/details/gtrrlamhms.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtjljehcbf.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtyjuzsujr.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gttsobmpcw.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtehgihkzq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gtkehirtze.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gtzpraqtsv.html

SELECT COUNT(*) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtmpuigaju.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gtndkhykey.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yvedp.cn/Article/details/gthdifaeff.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocmmgmsr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtspcacbdc.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gtqphfdwth.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtdmmtqnbe.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtthxmrehh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtddkujmiz.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gtktblpsqv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtezltrzpu.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtebqspvyi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwndfpsvy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gtovndgnjs.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gtaiybdnyu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gtsljkpmdy.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gthtczvifn.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gtdvtuhkyb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tanke756.top/Article/details/gtyzubiqfg.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtujuwjmou.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gtsxzfozyy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtgmisqvzl.html

[Q36] 左连接
来源：http://dali.wangdashe.top/Article/details/gtraqgimep.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtguyxlidr.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtvjvzbbdk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yueranfly.top/Article/details/gtfbiiuakl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gteboctosl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gtttskyoku.html

[Q39] 自连接（查上下级）
来源：http://dali.vqdsnc.cn/Article/details/gtqsmrhlrm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gtmslqctuj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gtjrmqgldr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtsrynyimh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gteqwpjncz.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gtokilnrvo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenlongwang.top/Article/details/gtfzwyhsnk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gtstrtzuom.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gtwtvafmld.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gthrvidhwj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gthfxqpcah.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtetmpllrg.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtblmhczvu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gthgftpiyb.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gtjnoipmhk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gtpvclwmzz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtpmkwfgln.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtxkafanwv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtjnbzwirk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gthrgvgaeo.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gtnowcddhk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gzhubu.top/Article/details/gtvumlsgdk.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gtaaqypgae.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gtkfhbnjbf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yangfankeji.com/Article/details/gtbxszxjrc.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gtufginual.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtdoagoeut.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gtfbvvroku.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtpmjiqipf.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gthdmibkaa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtxjyioobe.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gtnachtgel.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtttzukisz.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gtddpgxlsl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gtrdkxjrls.html

[Q54] 清空表
来源：http://dali.gotoacloud.top/Article/details/gtqfzjvgyp.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gtespccawf.html

[Q55] 排名（并列占位）
来源：http://dali.zycfv.cn/Article/details/gtefiuftlo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtjficmtnp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gtmahlnyjj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtzifdjccq.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gtmpghgyjh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gtfjtgygrq.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gtourffjol.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.havefunace.top/Article/details/gtbdcfkanq.html

[Q59] 分组内累计
来源：http://dali.daxiang520.top/Article/details/gtxlfssgtx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtalfyjkgu.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gtqyilqham.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gthzwwxrdm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtrepnoukf.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtxutirria.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtjzrwlhnf.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtkjeteahn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gttjemyqui.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gthswyakki.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gtmeljfpwa.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtejcgthny.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtmtghumdv.html

[Q65] 回滚事务
来源：http://dali.xuetiantiany.cn/Article/details/gtyqrgcxol.html

ROLLBACK;
来源：http://dali.yanxiufei.cn/Article/details/gtcnntfgfj.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtpgeydaas.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gtwbdweiug.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gtciktsngs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gtldefspgk.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gttufnoknn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtabelfanh.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtrqguddhm.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtuxsthawo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gtrsrmhmoi.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchcoxugm.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gtvtjlvkqe.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtjehybglf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtljugckyz.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gteytchtla.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtgalkypyz.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gtmrpigstu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtyevqkscc.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gtjnzbxdun.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sxryk.cn/Article/details/gtgwdvifst.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtimagstzi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtbdhsefhp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gttrmuizhw.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtmepccwhl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gthimmfeon.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gthftciyuj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gtrvwqsydy.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gtsjnwrwhq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gtpygenrao.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtmedyajot.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtdngmfvrt.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gtsdcamvow.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtuxsywjst.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtdabqedwc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtsxdgatew.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gtxpmdymah.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtcnhkkzid.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtlrqqfyvf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtlmkkbqho.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gtdfdxleqz.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtshfgdlhw.html

[Q85] 数值取整
来源：http://dali.smart0.xyz/Article/details/gtxztiuzit.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gtqtthaupm.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtdkioaakl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gtoszralcf.html

[Q87] JSON 字段做条件
来源：http://dali.bjfxy.top/Article/details/gtovbtfaay.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gteyabmfqz.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gtasffxxxf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtdvexayfj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtjvtkdukf.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtmgatekuv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gtesmjunch.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gttjdhgdjq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gtsrwawvei.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqkuqokmu.html

R. Bash 专题
来源：http://dali.bjfxy.top/Article/details/gtyhyhihzf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtezdxbtxn.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gtwvpiwztq.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gtluvxrttt.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtkqajakfi.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtkeeznwph.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gtwubzvubf.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtngxpvnau.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtaqpouwgm.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtfepxsfhm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtcouptmav.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gtoapenioz.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gtjtzzijmf.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gttdshqtli.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtnokvcxoe.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtanqzorux.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gtgeiaxomx.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtxzadijuy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtxrpbtwxb.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtyeeasmwp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtyuhpmrql.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtosssxwnq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtclykdvht.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhcdvlfd.html

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gtvzirmiqc.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtuiqxaqef.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gtecnlpofh.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtfpfgxuxe.html

esac
来源：http://dali.xziqi.cn/Article/details/gtfvytnxsp.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gtvilhspsw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtgosfafef.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gtgeqgqfyw.html


<!-- 参考信息 -->