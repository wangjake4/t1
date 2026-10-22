代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gt2jkaaeixa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gt2ijfctcry.html

[P03] 生成短随机字符串
来源：http://dali.pycfn.com/Article/details/gt2bsfwbxwm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gt2ihjbopyo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gt2gzrdkkeu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gt2dzdajowz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2pvywgxxw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2zrkcyuiy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ybcxt.top/Article/details/gt2nerkfawa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gt2dfkupquc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gt2ryctsmit.html

[P04] 求长度
来源：http://dali.ehwqpu.com/Article/details/gt2afhvilzd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gt2mianmupv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2brlfzunr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gt2qnepauhj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2awgngwyx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gt2lioaocmx.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xedgtljx.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlotvzvg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqinavjk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gt2ufuzevao.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gt2oulwvwrw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gt2avzjlcmm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gt2nbpoqgfz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gt2idtzrmif.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gt2sxyxzfnn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gt2fbtbgnjo.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gt2uurhjmrc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gt2zqektlro.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sxryk.cn/Article/details/gt2giqgchxc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gt2weccnpsv.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gt2dkqniroo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gt2wveltnnx.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2bhtgjxbx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gt2zxxjftzu.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gt2eahnweit.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gt2swksnnmh.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gt2rpdhkuab.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gt2bhxoejre.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjiuwtoo.html

PHP:  // 手写时间戳比较
来源：http://dali.yuanzhike.top/Article/details/gt2ebgxmolc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gt2rkcobiod.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2amkihmei.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2cxbnzggb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gt2mbxaffzn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.9152youxi.cn/Article/details/gt2leipvvtc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cheryme.top/Article/details/gt2ktfabvge.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gt2mjhqfhrl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gt2suehqemd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gt2qessvnyy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gt2aiujxnrz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zutuseuj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gt2tadmdywp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258888.top/Article/details/gt2mgpfntsj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gt2cmzcwuzd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkzbeagu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojpxxdny.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.bjfxy.top/Article/details/gt2xnbluits.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hjiyvcvf.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gt2ammbjshh.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gt2gifdktsp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gt2osmlxgsz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gt2jtwtoaju.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gt2ebwddzpz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sweek.top/Article/details/gt2juiuprsv.html

);
来源：http://dali.bjfxy.top/Article/details/gt2giuctnoi.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkklwtx.html

CREATE TABLE orders (
来源：http://dali.cheryme.top/Article/details/gt2uxuykpgs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2vgqaxsqu.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2ghuapvyi.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhotksdj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daxiang520.top/Article/details/gt2bdyevjhs.html

);
来源：http://dali.xylfe.cn/Article/details/gt2ncuktvbm.html

[Q03] 增加列
来源：http://dali.aizwys.cn/Article/details/gt2rsekoiiu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gzhubu.top/Article/details/gt2hrkxdgql.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gt2mohwxajd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gt2lfwxfvhp.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gt2quafolan.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2sohsvqwe.html

[Q06] 删除列
来源：http://dali.sufxvd.cn/Article/details/gt2uaznocna.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gt2yskgfaao.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gt2iarurdmk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2lijhscdm.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gt2xxzccozu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gt2svdftogx.html

[Q09] 创建唯一索引
来源：http://dali.0kj1m.cn/Article/details/gt2yxmtvwau.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gt2eshmokkd.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gt2kzpayfri.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2rnbagtav.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gt2juwgjmmm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2vfmtnlsg.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gt2gacyfyfo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gt2xpvmxvqx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gt2auwchggg.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gt2ujrkdpme.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2nomnypug.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gt2fgefqhlw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gt2vsnhuhbg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gt2ucxovwwa.html

[Q15] 查询全部
来源：http://dali.vqdsnc.cn/Article/details/gt2fegsmjbp.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2ewfmftpw.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gt2azllrzgs.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2kzbxopgz.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gt2nficoikh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2apawflbi.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gt2qrekmdxf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gt2nrtjhvhs.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gt2vvefopys.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gt2vqzrkmqf.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gt2yhgnzlzl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gt2bqfumbtf.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gt2uzrikkek.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gt2mgitpacj.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olyfsqse.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gt2csibzisx.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gt2ovvzeizd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gt2yhjnksco.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gt2bpdfdooi.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2fristfcs.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gt2nvxrppso.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gt2otornnrz.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gt2zfkvssyu.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2tevuvrnr.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gt2wffdrlfj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlvspai.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gt2vjjegjat.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2xvxctfud.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gt2fhippgee.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xaftwffb.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gt2whndxtje.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2umifsqih.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gt2ahzvbvep.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.0kj1m.cn/Article/details/gt2txxhfdwb.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjtebcsb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2kupewydo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gt2jagmpkon.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gt2ntiafpcs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fzhhl.top/Article/details/gt2tuaxrgxk.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gt2nunmagdk.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gt2vmczuqth.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gt2bpyhmyan.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2xgemtfok.html

[Q35] 内连接
来源：http://dali.c1oappe.top/Article/details/gt2uqedakmm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gt2yknyrsaw.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gt2kwxtuajl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gt2skuqxpdx.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gt2hbkbqgfa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tagspipo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenzaomai.com/Article/details/gt2xeqxgfrn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.havefunace.top/Article/details/gt2zoinakav.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gt2kpzhznxq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gt2ywxuavkb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2tymyqekb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gt2qwfcgwvs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pengpengdd.cyou/Article/details/gt2secbmrkj.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gt2jnplaqds.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gt2fuhdewvr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvjjesym.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gt2ocswntgs.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2qiecffku.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gt2vlzrneul.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gt2vldlxzhn.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gt2liscvbrq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gt2ttfxthcf.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gt2bgogfxih.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gt2mdyerpdj.html

[Q45] EXISTS 判断存在
来源：http://dali.chenlongwang.top/Article/details/gt2utskoacj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsggqsda.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gt2ewiymhdv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuwyzfrb.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gt2pztshchd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gt2fqkhyfai.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gt2qedgmkiw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gt2nmxzlbrw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yonumen.top/Article/details/gt2jhrhgfcf.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gt2cvqbsagd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2iesmexva.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bblmhmpv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyphqht.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwfekpio.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2kjrjkpba.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gt2mqhkhsjv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2yyqqprqh.html

[Q53] 按条件删除
来源：http://dali.sysykeji.top/Article/details/gt2pvggmysc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2koqkyukx.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gt2zxehqjkk.html

TRUNCATE TABLE logs;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyiajcmt.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gt2dpczmwkk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gt2mggyayyv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daxiang520.top/Article/details/gt2wzwbdfxd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aiynvnqs.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gt2nrhtjsbn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2zjfglvrj.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gt2daglbgzw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2kwkmxbbv.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gt2fdzeehot.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2ogxfefgq.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gt2zvwrszux.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gt2ttbusrrh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2nehwmogz.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gt2osouwgfz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2ctgyhckm.html

[Q62] 分组占比
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlynvxrd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2kwoicint.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gt2sgdtbqba.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gt2qjmobqxa.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gt2ioogqwrq.html

COMMIT;
来源：http://dali.pycfn.com/Article/details/gt2pduyjast.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2wrqxjzok.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gt2txplhmjl.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gt2jklbvkmo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wkrwgdai.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2wxokhtjq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gt2nfrhomee.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gt2cvcfchnb.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gt2elazkrny.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gt2wvfkeenn.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gt2ooabjkbw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gt2flonpkjj.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gt2zjhzqqci.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gt2nqgglxbr.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gt2hnaeyfvs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gt2pzyozqph.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gt2feuybavy.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bewyblsf.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gt2xapivifj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gt2rlabszek.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gt2neewfigb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjimixz.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2goukiaka.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2xarpcban.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fgpipacl.html

[Q76] 按天统计
来源：http://dali.zhengqikj.top/Article/details/gt2motyewux.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gt2havagdhq.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gt2eeailniy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gt2wzyvotye.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gt2cqstjxyc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gt2enuviqtl.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2htndxzrr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gt2chwnxhwl.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gt2ozxgvvop.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2aasckzdw.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2yslymafz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2seybdifi.html

[Q82] 字符长度与字节长度
来源：http://dali.iojbl.cn/Article/details/gt2iwmbxyrm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2usmfoqqx.html

[Q83] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gt2klpvicii.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2shecambe.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gt2bpnscvyy.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2vpupuoqg.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gt2comvhlet.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tian-w.cn/Article/details/gt2xrpuvbcf.html

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gt2cncnzjom.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gt2gjijzptu.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gt2uqgibiku.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gt2gtctvcvc.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gt2jxnrtuve.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gt2bptsckus.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2tvoamver.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2shpnafrv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhnqtrac.html

[Q90] 生成序号列
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpjyqfbu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gt2xlbmzyki.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2dpvagxfm.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gt2bycsbuoc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2jgrxxrjc.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gt2zzsypyii.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gt2ttuskprl.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gt2sdcztrhh.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gt2jxffmrtq.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gt2kiibstjj.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gt2rsrzgvyq.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gt2mfzlsogf.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gt2dfqmwkpv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gt2hxaaqbtl.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gt2ikiaqcqy.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gt2lkmwqydf.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gt2gfyffths.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2uelsaotn.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gt2hxjrfvfw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gt2iadakchl.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gt2kuotnmiw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.smart0.xyz/Article/details/gt2vddafmem.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gt2xjmecrac.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gt2bfgluchn.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gt2alzgggwa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gt2qgruzczz.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gt2npiiawgu.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gt2nladmphg.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gt2icyxpeaw.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2xlikabqz.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gt2phtykyij.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kafwdonf.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gt2sadlejiw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybievbby.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gt2zkiihbsy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adhgvelj.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gt2deauxamk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbostgze.html

[R15] while 逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpbhknnv.html


<!-- 参考信息 -->