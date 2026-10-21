代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtadzightu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gtdutxojil.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtqwbgvdry.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtluiymhkb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtmyqocnzb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gtlizitooc.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gtyzkzsgpj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtwucbdvhp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yvedp.cn/Article/details/gtzjoekkae.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtbwzqcsdh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtpatdyqgl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gtbmxeacvu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmpaqnnd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gtbwugrmer.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gtjjbabfly.html

[P04] 求长度
来源：http://dali.ehwqpu.com/Article/details/gtpbumtzhp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gtasawnell.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtndgfcgmz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtetpdtptc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtvxtqukns.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtjvchxjqq.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gtohjpyhxq.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gtmyyxvyjj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtwzyniose.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gtssnbjtph.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gtspnaepcu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gtitugswuy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtjkbjxipw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtfsfbhdqu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gtqvvlshwr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtacdwztwm.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gtswcivkcx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gttgfyjsvj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hysaishi.cn/Article/details/gtkynwhneu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gtkjbuflqb.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gtclzgdmfr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtqxoldbko.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtypilsltc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtlbvomyvw.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtrcoguvmh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gtkhlwfjtj.html

C#:   if (x is null) {}
来源：http://dali.jqgfzy.top/Article/details/gtybrkvjha.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gtznwblmln.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gtinjyvhcd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gttdtsjuds.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtrfodbhky.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtxliqbsth.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnxbmvfqc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gttwbvnobr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gtyndobecf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gtmmgqkbqs.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gtheiddxrr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gtkvbskrfz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gtqkfhgvgi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcrxibqe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtjmmysumf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hywenlv.cn/Article/details/gtanpxlifz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gtlqkjwell.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtysqfpwmz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gtnkjhseud.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcdoymre.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjblmzao.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpjydmijh.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gtckldidkl.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtjyykzgxa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtxbhgdbqs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtxnhoffck.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gtupckejzo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gtqpupvsty.html

);
来源：http://dali.dashuyun.cn/Article/details/gtmggdqlxc.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtzgvbnyji.html

CREATE TABLE orders (
来源：http://dali.hammf.cn/Article/details/gtfgzdghmg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtqbiqeshp.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtxdsjnffm.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gtnmphrxoh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gtwfotziwr.html

);
来源：http://dali.zhengqikj.top/Article/details/gtpuehwbdv.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gtqdmhfvzn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gthsqwnqpb.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gtgsufohru.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gtwnpocaqr.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gteyjkzmxp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gtvipgfmid.html

[Q06] 删除列
来源：http://dali.zhoulong.xyz/Article/details/gtkiakjalo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtlpxzptsc.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gttfqbvgcu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gtjqzqfkgt.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtmywgifdp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtlipcjsnk.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gtfeqzvgws.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gthhubjncz.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gtkinrxgpr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtxxrndwcr.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gthbehblip.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gtgoxjnqbb.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtzzmwcqao.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtncqoaunr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtpwsxxqcc.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gtdzanfkdn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gtghtbdvvh.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gtiavjddng.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gtmppedciq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xylfe.cn/Article/details/gtuzeyvzqt.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gtuzsajkzt.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtkhjgicps.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzrehbtj.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpmidhmx.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gtqafcsvgk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgzbmdzr.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gthwhbafxt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gthdbfwlml.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gtrigtwxpc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gtsaqjmexo.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gtftnkcgld.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gtnwhhzhpg.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtnngcoqtp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gtllmnpoom.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtyuocveer.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gtqnbmtzpv.html

[Q23] 分页
来源：http://dali.yongpay.top/Article/details/gtdvidrivl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gtyahmnyyy.html

[Q24] 去重
来源：http://dali.9152youxi.cn/Article/details/gtpfzgznmw.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtmabuebrc.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjoocugjh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gtcpxkdyhw.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gtellqekvm.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtxmemcysi.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtdbhufrjy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtrttlfvrk.html

[Q28] 求和与平均
来源：http://dali.yongpay.top/Article/details/gtzterbmzd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtxhnebznq.html

[Q29] 最大最小值
来源：http://dali.tanke756.top/Article/details/gtdkklnzqu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtuzakqsuh.html

[Q30] 分组统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjnzrolt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gthgwbapox.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gtajhwmeoc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtrnrffchk.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtfnmpbmgb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtbjgwonpj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daria6918.cn/Article/details/gtdsdpwyrb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gthailvtbq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gtuynbuqmi.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gteogtujae.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gtsoolcyct.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gteaeezwlm.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gthepbsrqq.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gtlwsivwlo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gthkiscmac.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtxrzamdor.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtujhxhwbv.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtnhahqesi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtyuptahhc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gtzujuqhhi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gtpctkghbf.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtnmwrobzm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtuxtmccmp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtevlscnne.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gtzbpuzwqh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gttaaatioh.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gtttvuggua.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gtbvhuliol.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtivbdxdxt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cheryme.top/Article/details/gtdffxjjlg.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorrazfgr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtjhqyisxr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gtvyexojjr.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gtcessqnec.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gtqtbabmel.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtryxxsits.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gtfgwimdhk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtsiisvles.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtiikhrwem.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtjqkkznbq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtjijemgqj.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtasegufag.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtorizizad.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gtwhzlxaqc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gtqolphkxz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtcvmzinne.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gtykeohobj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtqokntihf.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gtdwcjxdqz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gtpysdkhsy.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtttywvtzk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gtpaoroagx.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gtzoywszpw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtpltwbshp.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtovyanbfp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtdjlcoaom.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gtbgwohotv.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gtznazwplh.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gtefznqpvo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtiihqsyho.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtjeuhikzh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtiqnkexvb.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gtfhkodvsy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtjtzyijsi.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gtaccjoepq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtwqappgrv.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gtwhrlhpdh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtakdhayky.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtjkmctzzo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgfzy.top/Article/details/gthbxqclyq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gtxbehkrky.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gtfgfnyzie.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtnhzfnfyd.html

[Q62] 分组占比
来源：http://dali.xinyue.icu/Article/details/gthdvufrfi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtydvcjvaj.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtlhggjfse.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gtwhhpouyw.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gtqxbfluup.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gtidkguzsi.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gtrztqiaud.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gtalsdhruh.html

[Q66] 行锁查询
来源：http://dali.yangfankeji.com/Article/details/gtgudssyen.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gtveymobgh.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtlggxmzgd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gtwbdnosod.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gtbnvccjtk.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnglxrzb.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihrydxmc.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gtdjkdlxen.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gthvmftaky.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gtfdbvphrs.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gtpmxmiiul.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gtiuhfbuki.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gtedbmuthl.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gtqbcauxcp.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gtiefnedpz.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspytigig.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtcjkoegex.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdmactuo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gtjstevkum.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtfczjmrco.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtioomeogl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gtlfpmdlwc.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnyvuzbb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gtwgnfydph.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gthaebvwsw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gturelxexc.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gtvdowpdkr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gtejmezmhw.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtjznvazpw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gtxdexghcf.html

[Q80] 字符串截取
来源：http://dali.ydzc1.top/Article/details/gtjkdacqka.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gttuiiwfwp.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gticaciaek.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tanke756.top/Article/details/gtxsdwmzlh.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtyryznlbc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtscaukisz.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gthmykpoca.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtrandfddt.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtezwvtlyo.html

SELECT TRIM(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtsfcxuhog.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gtjqldbqce.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gtgnuyxuan.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtdkzzwfpa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gtvmxrdkdh.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gtbckhptwr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtbohduygf.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtncgcuyhd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gtvpgoyajm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gtjaleakmc.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtayrscssk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gtjrjtnfyj.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gtlhdcjhjv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtwhtxdens.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgaliizas.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gtqlvsdtkl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrwizvlex.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtyjblawbi.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gthhxmafnw.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gtcqvuqqnx.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gtfjkzwwvy.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gtlylmcxxp.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtfvlgusje.html

readonly PI=3.14
来源：http://dali.yongpay.top/Article/details/gtoljhywqr.html

[R04] 位置参数
来源：http://dali.cucudq.cn/Article/details/gttlwzpzbn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gtyewxvqez.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtrycauhvx.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gtdiqjzohh.html

[R06] 判断命令是否存在
来源：http://dali.yj202588.top/Article/details/gtxcedfwdf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtcoqtgkju.html

[R07] if 判断文件
来源：http://dali.sxryk.cn/Article/details/gtqroqolzd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gtdgdlwfgf.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtknnukgyo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtgrpczqmr.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtrkpursjc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sufxvd.cn/Article/details/gtmukyfeem.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gtudsfbqcy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gtiwtryqgn.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gtxkdwddmo.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gtxfwlddut.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhbvjuxr.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gtjeogncun.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtguqebxfz.html

esac
来源：http://dali.xylfe.cn/Article/details/gtqdidfshd.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gtwgygpodl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gtfjjstsjm.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gttvhgsbdg.html


<!-- 参考信息 -->