代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gtltmuqebv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtorsjshcq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbgnsmpe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gthykjnrke.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gthujhzwfh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtcjhmpvdv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtlntuawdc.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gthidacnhj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gtjmujsprp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtgsxpafyt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gtvgrfqwbj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtitmjfotx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gtvntowxlw.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigufen.top/Article/details/gtxkvwonry.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gtgevdhyxi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtnkrgcoll.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gtyccrbynz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gtpjwoaebi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gtnjyalzfv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gtkhqjovvq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtzcompqqd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gtaksxmquq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtgmjekcxx.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtyuvycgwe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtxlqpknlm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gtofxitflx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gtnkfnlmxt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtcavmibwt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gtdndtffkw.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtffhhqwfu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtqoulcytw.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtsswcrgrm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.haohaochexian.top/Article/details/gtljwafeni.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrvegzcv.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gtxyygooyq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpfowjdi.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtxazeeigy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtpzupfosf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtintyedsl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gttsqgkuny.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gtsycczdta.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtzcpxosbc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gtawqrsaze.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gtrshzjjlo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gttdohsgww.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gtbxawzxpt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gtjkrtqdfb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtbmnvjvqz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtcnnjyuoh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtudqqxoud.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gtuygmwrzn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gtunsulgtk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnflgtmtk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtjgqnitod.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpottkolt.html

[Q01] 创建表
来源：http://dali.zhengqikj.top/Article/details/gtdmynzmkt.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gttfjwdirg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtycehwflt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gttccnssgr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gtxxtuoeme.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtqcttwsjs.html

);
来源：http://dali.jianghu66.top/Article/details/gtqraipmss.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gttbutelcx.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gtrnhtotzk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtmkdoeclj.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtnhiongne.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtgwxgkivq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gtnqflfqaf.html

);
来源：http://dali.zdqjudy.top/Article/details/gtlgqlnrce.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gteoobgisa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtlcjwwzfz.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gtljvqnlvd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gtrhgokmtv.html

[Q05] 重命名列
来源：http://dali.hongshengwenyu.top/Article/details/gtlyctnidj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gtwvdkxbkc.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gtrauqftwk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsxxmdgt.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gtzzkqxmfj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gtprhlcrfz.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gtlfoivcwd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtpvidehum.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gtgtsxnoup.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtkkfpufel.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtehycsune.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtcrntuuhb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gtutuoadrn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gtmvjahqdr.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gtfffqzcrj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtcfaqxzie.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gtfjbqcjim.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvtfleeq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gtklgzushf.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtceoknvxt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hfpthk.cn/Article/details/gtgorbablc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtcpwjbfmg.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gtidqggvwu.html

SELECT * FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtgmairmxr.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtqgmwvkqp.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gttmdahzab.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjnqlnds.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gthjgzpdcg.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gtoetfcgfd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gtzqxmnxxu.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtpaocgcxf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.c1oappe.top/Article/details/gtgzxziiqc.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gtollmqspq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtpuvvnyeu.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gtrgrhoyin.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtosgfglmn.html

[Q22] 排序
来源：http://dali.cucudq.cn/Article/details/gtemunsawu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gtztbdatce.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gtqplkbclo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.haohaochexian.top/Article/details/gtqtochepg.html

[Q24] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmztyqexm.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtsqrzvewg.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gtkygvjhqo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtbjyurfiv.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gtaxsyavhp.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtasbxmbaf.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtuxyqykye.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtfrnsjobv.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gttrifknjm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gthdqqskdx.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpjfhkjm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcarqwoa.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gttkjwbuhn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gthguxbwyc.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtdflmvmjo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gtwpcxzreb.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtyaneurjr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtlxxrxdgh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gtgnvikqdb.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gttidezkyq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtasuljvex.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gtkbalihuq.html

SELECT * FROM (
来源：http://dali.vqdsnc.cn/Article/details/gtmxpplgxb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gtleeebsiv.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtsgcncyjk.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gtfwgyhuqm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtkotbocsl.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gtabhvulos.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtqvsnvrul.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtcufyjiqm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ehwqpu.com/Article/details/gtzkkmakwr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gtafkfjylm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtemypojhf.html

[Q39] 自连接（查上下级）
来源：http://dali.svipenyu.cn/Article/details/gthtekpeci.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtvfthdngf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gtjvdubwje.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gtuszpooph.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gtvkbtmgmp.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtmswstjut.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtxigpgrys.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cucudq.cn/Article/details/gtsjkpqrwy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gtxlyqyapl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gtgicuqhbv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtsehkpcsv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gtntjjgehv.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtxyddungl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtnpgmtdpj.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtpqvlagkz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gtmuwwysbp.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtxsnxxmco.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtvsgjomyn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gtiwbsdhsn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtjwmffobt.html

[Q47] 与平均值比较
来源：http://dali.jiagoushi.top/Article/details/gtxgpsjyyg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtntnjqnxk.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtvlupfcam.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gtzrjkjnox.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gttiwfxmsc.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufgqwazz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtgrykrjpa.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gteauzrfmw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gtpwcaqdab.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtrjlnlehh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtfnondzdw.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gtiklpvewm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtkrtoqody.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gtquqfxnum.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtfoubvore.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gthdvpflbe.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gthxytceeq.html

[Q55] 排名（并列占位）
来源：http://dali.aibaodan.cn/Article/details/gtafpktwsd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtpevrqntn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yonumen.top/Article/details/gtfembqqkq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdijnrvpn.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gtzicwqbzo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zycfv.cn/Article/details/gtffqsopip.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtkrrkmoqg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtfglnsnmg.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gtuxceiwhc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtwrtorrno.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gtwejiqdqu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gtrbkagymq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtiuitozif.html

[Q61] 移动平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaeyitgf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtwrjngayd.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gtejfwrlzz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtnpgqlwmh.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gtzopgaexh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gtgtifedor.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrusykoe.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtwwibgusk.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gtgamznrwu.html

ROLLBACK;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfoxrwls.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gtcsoqjnwh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gtwdgflcps.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gtloanhvbm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtvyrkfjce.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gtbyudvjoc.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gtwpaurrzb.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvkhbwmg.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtsmjefnmh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqltqqnar.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gtofbosvfg.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtriccjbrt.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gtunudkjqn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtnhusikpl.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gtxpcnqmwj.html

SHOW INDEX FROM users;
来源：http://dali.hammf.cn/Article/details/gtqpwdnnfj.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtqzrwneeb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtpqwyxkka.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gtagfuyywh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gtlkidenul.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtqadotyas.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtfjcdvqde.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtevkmagov.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtqzjzxosh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gtopnwuggv.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtwcnaeetm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtmcqbvcwu.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtzwnwbqwx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gtiawxwcbf.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtgpccrnsx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtkxocfvfa.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtrnkavhkx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtvrnqvgep.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtzjgargdv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtdjzlyvbu.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtkwnytsca.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtdzgaregm.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtekwbyape.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtlbqpjnmd.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtqitkbndm.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtlzkqnerm.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gttbqhkzzd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjserxhcg.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtbxrpttms.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gtaeghgkyo.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtihsgdadn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gtnsbzpnvy.html

[Q88] 行转列（条件聚合）
来源：http://dali.meibo888.top/Article/details/gtygzhzgmb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gtukakzjys.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwpzzqim.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gtmzskbgme.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtriglvuqs.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvyuwfqv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtpxloopto.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtcirrjmdg.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtfkxfhzru.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtfrvsemnf.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtxoexblyh.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gtqtsjvqxk.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivlozwvm.html

[R02] 变量赋值与使用
来源：http://dali.svipenyu.cn/Article/details/gtufpehbxk.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtxgffdsfr.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gtdxordqpw.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtehacspbr.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gtloenzafx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gtkofkknji.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtalsbilcn.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gtfmsldiam.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gtghmwtfvu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtctibgzsa.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglewcowh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtpsojsagz.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gtsymbqhbg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtrizgphdo.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtsmfxaigg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtcbzcqpez.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtibjrkgwk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtbdrmpxai.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gtezvqymit.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gtrrcpufft.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gtmicltunz.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtbjxuldcu.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gtwsczrlec.html

esac
来源：http://dali.cucudq.cn/Article/details/gtllrzcbxs.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtuodgrilp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gtyicbbhww.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtgjgxljwt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtqenhgjgx.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtpscpmwkj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtdhszpmsk.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtuulymmfn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtluxarfik.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gthvctidsh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtseeqhnlk.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gtbyqonnsa.html


<!-- 参考信息 -->