代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtsqyufbpe.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gtlmynlxyn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtpqiicyuc.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gtwxskzszf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gttapseybw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pycfn.com/Article/details/gtnafgqkej.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtbektgxeb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtonpklgaw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gtrtvzusjn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtfoqmqfsi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtepzkckvs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gtsoquwmji.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gtvwuitxwt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtmajyxhum.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gtprgmocmq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtynvzjtte.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fzhhl.top/Article/details/gtgtkczziz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtvohgncmy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtjoxssiuz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtlpsmrqkf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gtplezgqpf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtkyiecmxz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzsnxyoc.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtbmqzdtqi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gtfwbzulvv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtqulixguf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtkedrkyvi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtdplwopqo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtjbmeuesa.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtpayfokot.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gtyueuggwj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gtyexrtlmr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpibedcs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gttebmuitx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gtygwcbmdo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gtgsmsrhic.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gtpolicrac.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtcdqgikta.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtrjxwzctk.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gtvakhflnw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gtjwlqumfi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gtudpwnqxy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtaetkqpjc.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtyawbahyo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jlsjyb.cn/Article/details/gtjzocxxpp.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtdpdwgtnx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtgqiphrqg.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiqtzlyp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gtiggicnrk.html

C#:   if (x is null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmpqynaje.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gtqvrommet.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gtqehkvjgc.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtppuvrqeo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtughouazd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gthzmpdmdq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtiumomybp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gtpbxvccui.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtugcokcey.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.vqdsnc.cn/Article/details/gtrrfhawbj.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gtnvmpokil.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtfdouhtoz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtbqhmbrlm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gttqvgzovt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtppzpsxgr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.snrcjt.cn/Article/details/gticygqcus.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gthabveryr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gtqlkaxtgn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtqsalkusu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtiojxybno.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tian-w.cn/Article/details/gtfcgmyrhi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtckvksrgs.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gtcvdfoghw.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtnoagqmzx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtdxldhafa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtmzvjzzbl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gtnomednvc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtequwhizz.html

);
来源：http://dali.jianghu66.top/Article/details/gtvjnkbqvy.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gtomtkykdx.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gtfbvlzzio.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtszkoyghc.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gtlyuqoiyn.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gtcfnkgmpi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gtwlwzycch.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtgdlstadx.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gtgxhahmcx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gtebghzumq.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gtzykjlgje.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtlhunhkdj.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gtxzeoppyd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gtxbjtllgh.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtfgxkqiqt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gtzdmecjhj.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gtnbkffesv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtulknnyqb.html

[Q08] 创建普通索引
来源：http://dali.sysykeji.top/Article/details/gtrnhpfrkc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxnwwfdh.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gtghcfrygf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtkmikiubo.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gtcjkmfzfx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtessuhxyk.html

[Q11] 一次插入多行
来源：http://dali.zhixingplan.top/Article/details/gtkcvlxqvq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpumvimp.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gttulckpdz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shangyingyoupin.top/Article/details/gtkvkefteg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gtjylomdtv.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gtqytevnuv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtaliyqucl.html

[Q14] 存在则更新（upsert）
来源：http://dali.ydzc1.top/Article/details/gtckecrlxr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gtrppbcbpp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gthdzdslki.html

[Q15] 查询全部
来源：http://dali.cdnleiting.top/Article/details/gtsszbywvs.html

SELECT * FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtbjwcdafm.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gtyivwfjno.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gtdpcpfecp.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtwukpdvej.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtudcbtzah.html

[Q18] 模糊匹配
来源：http://dali.bjfxy.top/Article/details/gtbhmymehu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtgwqqybgr.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtqgeywhja.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gtidbkhfdd.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtdgtbmahn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aizwys.cn/Article/details/gtxwzzrguq.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtrlnnsemi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gttvcewzmw.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtvkpjkqjz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtpmzzopdj.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gtemcwaaoe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgufenzy.top/Article/details/gthlwrkehs.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucxdhqfm.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtyzvczvxw.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtmlyfglbs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gtibyflxeg.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gtfwbqbzgp.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtpsinejwo.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gttzakvimt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtcxoggmig.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gtkvabfucj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtdcudyowp.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gtxtpdrrse.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoglmcayp.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gtqwuwljxn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtdvlnidnt.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtoxsyuwbd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gtwvcccdtp.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtbjcwgobm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtlozjzsds.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gtkjyooxpn.html

[Q33] 多列分组
来源：http://dali.dashuyun.cn/Article/details/gtvzfljgig.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gttixbffji.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gtnlohjcka.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gtgkifmntq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlimnnzfw.html

) t WHERE rn = 1;
来源：http://dali.zdqjudy.top/Article/details/gtpdwewomv.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gtkwiomdst.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtjdnvhnwj.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gtexlxepsk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtwdohkkjm.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gtxmodjkxx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gthbkzpshk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gthhuerjky.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtrewbabqu.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtjmohyszm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gtzkvtmkim.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gtpxohnkcm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtgizkoulx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtolvayksv.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gtkuelunob.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ppjwa.cn/Article/details/gtzdslvtmv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.kuanghao11.cn/Article/details/gtbbjblhec.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gtypsrqsje.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gtyuxxachy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gtpqnugchm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jiagoushi.top/Article/details/gtajjnmahj.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtmnylxvfz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gtkjekkbfd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gtvmeqcwpu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.svipenyu.cn/Article/details/gtgwxcjpts.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gtdubtigci.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvycexxdu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gaohongyu789.top/Article/details/gtzylkhhat.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtojfmeibs.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtewaqjblo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtwqamsbny.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258888.top/Article/details/gtrnhnuxim.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gtppoipthb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gtwnssktdb.html

[Q49] 更新单行
来源：http://dali.aizwys.cn/Article/details/gtzcwljvzj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gtjcypiouj.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtwaqmrfuh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtzkunlnyz.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gtmoihmius.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jyoumei.cn/Article/details/gtdwsqjwzm.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gtuxbwdkus.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtodzmfynu.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gtafbpwxqz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslzanbgj.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtqwywwqjd.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gtivvutghp.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gtmtbvfaec.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtswxolafw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gtmqywpbkf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopuycmog.html

[Q57] 行号
来源：http://dali.ybcxt.top/Article/details/gtdzphuxhs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtfswoxqcp.html

[Q58] 累计求和
来源：http://dali.shanyushiyangtech.top/Article/details/gteyuqxezs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gtizdtipks.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gtoeablorb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmzzfrdj.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gtvmjbzabi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gtamhqgzio.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gtopssguoo.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gtbdwhgalk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtedevxxbm.html

[Q62] 分组占比
来源：http://dali.cheryme.top/Article/details/gtxrafuajv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtwpacoqjy.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gtniwgyvbw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yangfankeji.com/Article/details/gtwqxpozil.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtsapshifi.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gtbufcuxjz.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gtwsmukrzv.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gtrwtrodpw.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtqdzwwjbu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtyoljst.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggwwaqvp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtnxefdutg.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gtrebskzzj.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtawgohhrn.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtkayxmzyx.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiotfbnl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gtwdbxtndc.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gtlfzahjmy.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtlmfwzqwg.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gtctutrivj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gttgzxkmen.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gtejgoijti.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdnaqvhm.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gtetttfoac.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtetargutq.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gtcwqnbbqv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gticfjtoup.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtfpizrwqd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjfbefps.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtsenzjsoa.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtasmoxlee.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gttvepjmjq.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gtbzbysofu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtspbxtjhj.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtorbsuefn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.0kj1m.cn/Article/details/gtyoounzwf.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtntbayaqo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gtuximlwzn.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtheitdbyu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtromtaxtv.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtcavaeilc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxsmguba.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtftzxqxoq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtobmlnqta.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtrzwocfzh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtaxvqraad.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtewxkifiz.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtxkpdyrjv.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gtplgkzmev.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtzfyvrmkg.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gtgtmuijdh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gtuvvootmo.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtehjqmcch.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gtlgtbsphf.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigufen.top/Article/details/gtqiiogags.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtldzveifz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtvvwwmdpn.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gtcnqyuhkq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gttwvfzkga.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gtchsentmu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtjlxjrmob.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocbxojup.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gthfuhtind.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnomhgnfd.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtivcanjrp.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtaahyrgnq.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gtvssoxbnc.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtgeuaoczn.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gtqhtlkhim.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gtjsqkxgtk.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtvnmfpfty.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gtubpxxuwe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtalswlgkr.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gtcvmwiqdc.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gtggpiqwvy.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtmbxpyced.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdghbfryt.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtkkspvevx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtsayngljf.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtvkubhsxt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtaluvhxaq.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gtnaetjjwy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gtbhuszyni.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gtsqurngbo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtttgfroxl.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gtphofxjjf.html


<!-- 参考信息 -->