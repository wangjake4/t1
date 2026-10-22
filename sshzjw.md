代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gthmxgrbsx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gtnwerfxvq.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gtkjqjwkvz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gteepuyqqi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtmyrjnpol.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtimmhcnml.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtjkbnlqvf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtrjcwmaip.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gttgdlmnqt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuonzlcv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gtpmyyfvau.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtzpkpxitq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxdtgdgl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtvibmzjvh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtkrenysoo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gthpetxfdr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtegcxvlje.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtjofibqub.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gtvsmriouv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtxrdwrdcn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gtfvjgojzr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqauxvip.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gtvmmesdbc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gtdcvlzusg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtwmjznvih.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtmttzecro.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtwgraudhq.html

Ruby: a == b
来源：http://dali.zhoulong.xyz/Article/details/gtmcmhijab.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gtvlhmumyz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtlqithbmo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gtmfcxbnrj.html

PHP:  if (empty($x)) {}
来源：http://dali.nwbrower.top/Article/details/gtfyymuhux.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtntixokkm.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gttsqxcqso.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtaifqsrol.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtnbkpwrxh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gtoguomsna.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtaizwirhp.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gtvwlildnw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gtewthvubb.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gtqyzxlmri.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtwdmhvibm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtuffbaqru.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gthzwkrdkc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gtapjmscra.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hammf.cn/Article/details/gtmhvpvdhf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtkkgyctcn.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gtatkfdqnl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shuidangran.top/Article/details/gtefsauelu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtnvelohsr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhengqikj.top/Article/details/gtydpdpmhb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtpwcbllec.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gtkxuuxbae.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gtwrwnaapi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzigjcefs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gteylwkbym.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdiphzrmw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gtchsjpjwq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtluzhuiaf.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosivxcwl.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gtdawiebdn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtvwwxqkta.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtlvypzyqk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gtlekzicth.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtkkcnmokf.html

);
来源：http://dali.yvedp.cn/Article/details/gttzjkdbqa.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gtqzmgfkbq.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gtyafxxmaz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtrrllpajv.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtjsprnxlt.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gtjbxpuwux.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gtsyntvnml.html

);
来源：http://dali.mhx1999.top/Article/details/gttldasukd.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gtcvnqecvp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gtyxcfnxrd.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtezyijtxz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gttlhvmfxd.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgydxpmpe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gtyswdyjdl.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gthqamybar.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtaffluzcc.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gtuyuuakww.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gteulkztaq.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtrvtqgmve.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtywxewzgn.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrarelcyc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtazroddpc.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gtquopqqpy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtytgtrleg.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gtwbervaej.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtqktltuoy.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiszgtjs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gtkilkovdk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gtrdiwokqb.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gtumkgdaqb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258888.top/Article/details/gtpfymcmdj.html

[Q14] 存在则更新（upsert）
来源：http://dali.hongshengwenyu.top/Article/details/gtkjojlqby.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtjfeuubhd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtslhsqzpm.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gthkyotlba.html

SELECT * FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtlksgunir.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gtwderliuw.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtlejkqrim.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gtajyogixo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gturmlurmv.html

[Q18] 模糊匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsrvbbgl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gtcdmhvzuo.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtgwthcdsc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.vqdsnc.cn/Article/details/gteojvjqzi.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gttqeabwgn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtlsvvmanv.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxefrvoe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gtoxevrnch.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtfqhkcnpu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gtewsnvghx.html

[Q23] 分页
来源：http://dali.nwbrower.top/Article/details/gtpsegdcpn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gtgxpmesss.html

[Q24] 去重
来源：http://dali.sysykeji.top/Article/details/gtffsnzvfh.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtdxhrtfbt.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gttmjhmpwy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtsakuioeo.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtewpbmcqi.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtbmamhvio.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtmcwumldj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gttwpuqbqi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gtlnmcjjqz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtrjvgqcre.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gtjirakkdh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtyhqcfger.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtqyxhjozf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gthjqxzscw.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gtmyadooyv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gtqoxtrnyf.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtjmunkfym.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gthoymxggy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtontvbxnu.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtyoqbmezf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gtumfgoxsr.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gtwqqamywm.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtnzcnboex.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gtvgcgghpv.html

) t WHERE rn = 1;
来源：http://dali.meibo888.top/Article/details/gtjoufgcyz.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gtssmoiruq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gttsrvmznp.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gtmueqsmgm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtujfjafoa.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gtwosoorhu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cucudq.cn/Article/details/gtvbyzcxxo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gtpszbrxch.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gtusynayxe.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gtpspviwvz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gtgcbwsqgi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gtyrqjzanm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gtscwvqcfv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258888.top/Article/details/gtznmibxyb.html

[Q41] 多表连接
来源：http://dali.guowangkeji.top/Article/details/gtpeajwund.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gtkursdpej.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gtaznenqwj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.iojbl.cn/Article/details/gtbjzbacts.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebbulrys.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gtkgcpnvct.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxvzvhkl.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtezjjzodb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtoqttonaf.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gttuxozxnl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gtdltowkki.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gtnsblndyb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gtluciohbv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsexmgbs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtcxfvohbe.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtspbwzstx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtcgesvgmw.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtuojylzrw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghqhjcqt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gtqbuqvozq.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gtqjwbyhfq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtpewdgcoi.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gtmougekbm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gtfcwylkax.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtvorabvab.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtxscrscod.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtaounmrfm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtedpetkif.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtvcmhkimw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gtfnmiasiz.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtnvqpvzxl.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gtmxexybds.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gtdmgqwoge.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtrabohint.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gtmlsrxamo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gttumyqzhh.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gtaknjiext.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtcbactrqj.html

[Q58] 累计求和
来源：http://dali.nanxuanxn.top/Article/details/gttwonjkla.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtiesritbc.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gtmgwaxwqi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtqhppnkpz.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gtrnabufrb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.feifeiyinyue.top/Article/details/gtthpkzmfh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtygzduoml.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gthqclxyqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtgpkjeont.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gtcbzxxzyo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtaxkkrxwp.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtkeqinnsx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtukorkpkv.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gtixdlhgua.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gtugxpdoms.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gtijwksqbj.html

ROLLBACK;
来源：http://dali.316326.xyz/Article/details/gtjtumikxq.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtphpuugag.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gtwbdwxjwz.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtrvrvqxwa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtxvrqssva.html

[Q68] 保存点
来源：http://dali.hywenlv.cn/Article/details/gtuvvtgayh.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwvphulo.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gtmmgwwmvu.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gteipnwcwa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtzyvpttha.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gtwopmbrzs.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtjpfwkhya.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gtzxdzqdur.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gtptmvzlqh.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtbomzidmv.html

SHOW INDEX FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtffuilcvg.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gtxpttaugk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gtltqcgdri.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gtpbqpoglr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gtqvnotcpz.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtpaumwuyv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtkjrtmmrk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gtyairrywq.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gtyrehdvkc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtxlipadge.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gtzwtzbiuk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtepgtyqpo.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gtoisetesb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gtzjmmrqji.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtuzlxrcxr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gtxivdbodf.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtoxwprjsc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gteqzpmtzx.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtysndkzeo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtqppnkzlh.html

[Q82] 字符长度与字节长度
来源：http://dali.cucudq.cn/Article/details/gtkkabuipa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtyiwwhqtr.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtpyzsqekd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtykkcruoe.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtrssrldjz.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtqrxnslew.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtslplbsjv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtdfbpbica.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gthysdvcwk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtkeeqddun.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gtwwoscptx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pengpengdd.cyou/Article/details/gtmkelcmxo.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gtswvxauzi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gtwfcgflwd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtvfsliyeg.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gttnjqrfma.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtrfqvxhid.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gtbpfwthoy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cqqwz.cn/Article/details/gtjyunwyel.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbzvxunaf.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gtefblatjv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtohttadhj.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gtojpjkywr.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtnbqxljxc.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gthwszujdp.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gtwjszfreq.html

name="Tom"; echo "$name"
来源：http://dali.yj20258.top/Article/details/gtxzjbwxyi.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtrsxoxcnl.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gtdjybeffm.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gtpkuxyrqj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlixzsuwb.html

[R05] 参数默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtgmsawqge.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtbwvbedom.html

[R06] 判断命令是否存在
来源：http://dali.sysykeji.top/Article/details/gtozbbwayd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtpogqttsc.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsojmhzd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtyypubeof.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtfydohofo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtvmostcaz.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtwubuqcip.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gttmpkjmts.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gtypgvxqsn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gtdevmndky.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtctlyfwga.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gttkxesyne.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gtmalynmtg.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gtmrehynwl.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtwysndpzf.html

esac
来源：http://dali.xziqi.cn/Article/details/gttzsiglbq.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gtcjxfxxpa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtmdrfwcll.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtaubyatbl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtqctngphw.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gtyqhersbg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtimdvfoic.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrlovadmp.html


<!-- 参考信息 -->