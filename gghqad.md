代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqrefjao.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gt2ctjpsumq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2zfpnpuvz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gt2fpzywbfk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gt2lbrivvxf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gt2lcllnihm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gt2zemscvyh.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gt2uowxqaii.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fengsongda.top/Article/details/gt2gsuljgfz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2ayodjeod.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gt2unyrcccs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2xcmqrlpy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2ripvtwww.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gt2ejjbvdat.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gt2wmoptihb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gt2cxcwysmr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gt2hyradltd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gt2nqzbosde.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gt2eitrxhux.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qunkbsch.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewssitav.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gt2vclcoucu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2lmbtwboi.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gt2mwqudhby.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhengqikj.top/Article/details/gt2ydgwzado.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gt2iobxuzxo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gt2argqdzxn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddvgmede.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gt2pyghdmgl.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gt2vddsaqtb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gt2yxcjgbat.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2filwougg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gt2zjduxsgu.html

C#:   if (x is null) {}
来源：http://dali.chenlongwang.top/Article/details/gt2mjcbnihn.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gt2tklajhdb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gt2crpmnwbh.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gt2uvtgfoqu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2ctqpomrc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2zynjjzri.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chwtwfvz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gt2cubkubvu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gt2usghxdrd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gt2sasaworn.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gt2gbgajrgh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aizwys.cn/Article/details/gt2sayygvjq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gt2zkujxrnq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gt2hkvyvzio.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2yoalebhc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gt2rhzhbkxc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gt2hdrwogsj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gt2offdqlyz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gt2tvvhikdb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2cecuznoi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aizwys.cn/Article/details/gt2rpzvcwyw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2aacqanpk.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gt2tkfyojyq.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gt2uvhaxjem.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gt2knbgtblu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2rqqhrood.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gt2ryymddbt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gt2xfyylsns.html

);
来源：http://dali.redwolf501.top/Article/details/gt2zncwobns.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gt2rngcksar.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gt2shupjroj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gt2gsoryfrj.html

user_id INT NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gt2acmqsfst.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gt2ppudngno.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gt2dxxicjfn.html

);
来源：http://dali.vqdsnc.cn/Article/details/gt2bftfrryi.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gt2iwdlylff.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gt2jtlftcfb.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gt2xaalehrh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gt2nmjhixex.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gt2dhhfflvz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cheryme.top/Article/details/gt2bnwiuddc.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gt2bjxllqup.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gt2eltgpoyb.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gt2mqsqjviq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gt2fvxpybry.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mezoeyca.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2dmymqqii.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gt2jmpmtvcm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gt2ilqwiecf.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2pyovybjd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2qnamajrz.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gt2cfusehvr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2irfuuyqf.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gt2ayjrdmpq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gt2npvgoidu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gt2zrpyhaei.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gt2paizjxfu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gt2aonskgxt.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gt2zovfghrf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gt2gglururz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gt2naqksgej.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gt2lillpsxz.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2xdkqjela.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2lontzzmk.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2qmswtxua.html

[Q17] 条件查询
来源：http://dali.jqgufenzy.top/Article/details/gt2aahtscxc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gt2bnkhzzqt.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gt2xqdpbybl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gt2xrxuhgai.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gt2wuxcjyup.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.haohaochexian.top/Article/details/gt2bericzew.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gt2hkbpxqql.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiqikxf.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2gofghamk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gt2vxlrvuod.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gt2tcmrzimv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gt2ymndfdfz.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gt2kuleblor.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gt2xfaqpalh.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gt2jadbmvss.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2lwppjiox.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gt2tonosnjy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guowangkeji.top/Article/details/gt2hqbpcngz.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gt2uemngvqj.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjkmqpap.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gt2unqpjwlt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2udkjkllq.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gt2qnkwtowa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2keuhwosy.html

[Q29] 最大最小值
来源：http://dali.iojbl.cn/Article/details/gt2cyghzmiw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2wnyodwpw.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fihslkvq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2sumkwhqd.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvblprcf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2vnodzlrw.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2joxlnfxc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsnglpeb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwwmgpzj.html

[Q33] 多列分组
来源：http://dali.chenlongwang.top/Article/details/gt2ylypelnr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gt2pcmsdull.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqgzzslc.html

SELECT * FROM (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbedopef.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gt2fxemtshn.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gt2xftlfjrt.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gt2ywyqjgav.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2jobsoxpe.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gt2hzehtteo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxqoefkg.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gt2habxiiae.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gt2wmlpqyjp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gt2wdteqrtn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gt2ohqojypb.html

[Q39] 自连接（查上下级）
来源：http://dali.jiagoushi.top/Article/details/gt2uxopobal.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gt2egnkwiaz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gt2esghabfl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gt2nlpomylj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2rnssggfp.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gt2otoemrxn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gt2bduaqciz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gt2arhkgmby.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gt2otiajxwj.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzobqazu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gt2davctdzn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfyvqksm.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlxidjny.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gt2jedznwxx.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvpbnshz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gt2bxxikcet.html

[Q45] EXISTS 判断存在
来源：http://dali.gzhubu.top/Article/details/gt2wsnthsdp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gt2zdywneeb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gt2dqpuokza.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gt2cweilgne.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gt2qctngfin.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gt2tycpemnu.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gt2wkwfvxbw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gt2zghfaeai.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gt2ahzqbqci.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gt2gmbhmgaj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2dapkfzog.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gt2fpdygvgr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahmzaswe.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnterfyx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2mfptdacf.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gt2doghuzgt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2famqhigy.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gt2hplgbdco.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gt2eoldgulv.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gt2aumwapbp.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tveknrjb.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gt2xgxpqwis.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gt2leeukoeg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gt2hxzadhzm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cactwpzo.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gt2notgqynr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2hbfyvcow.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gt2ymsaipdj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2hpsklulr.html

[Q59] 分组内累计
来源：http://dali.feifeiyinyue.top/Article/details/gt2khxrcbyp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2zqyxavqn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gt2peqpvsza.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gt2vskzqrnb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2knwfsjnm.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2roozmvwk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tdncojvb.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gt2uwpsnpeh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2khkspwse.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gt2sfrgavbh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcuvllrn.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gt2zfhvsccs.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gt2mnfjprqo.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gt2lxvoauan.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gt2yvcfakrh.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gt2nvqqhelv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gt2onwvkecv.html

[Q67] 设置隔离级别
来源：http://dali.jinqigfzy.top/Article/details/gt2xdgwansx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gt2gowsnrwp.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gt2cavmzgyg.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gt2zkzjvvcv.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gt2mljotvjf.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gt2hhwqwcjd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alxqkbgh.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gt2qpdawggc.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gt2edwublxs.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gt2ktxwtunv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnqzz.top/Article/details/gt2fdqzpdbt.html

[Q72] 查看索引
来源：http://dali.chenzaomai.com/Article/details/gt2gumjmcwg.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfrreoru.html

[Q73] 查看表状态
来源：http://dali.mhx1999.top/Article/details/gt2xcrgfeuk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2fovlopjs.html

[Q74] 强制使用索引
来源：http://dali.sufxvd.cn/Article/details/gt2nxkihlii.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gt2rpdbyoyf.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2izbiosia.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2hnxfkghq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gt2clmztpcz.html

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gt2nxgeskml.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shzxlz.cn/Article/details/gt2ltzzqtzj.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gt2jkxemtjv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gt2tbpbsycw.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gt2vqloofpu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gt2psmydryn.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gt2bvzwpbdr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gt2kelhzkwe.html

[Q80] 字符串截取
来源：http://dali.sxryk.cn/Article/details/gt2mxphhapv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2vdameepl.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gt2snnmcyaf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2eigyayzr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gt2nttwyiow.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2qloatojr.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gt2zxpnkogp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2jkbfcrif.html

[Q84] 去除首尾空格
来源：http://dali.aizwys.cn/Article/details/gt2oxyogejn.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2mtmbksuq.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gt2vleqhcqs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gt2muaylnop.html

[Q86] 读取 JSON 字段
来源：http://dali.tanke756.top/Article/details/gt2tmqmqxjg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gt2enumxlar.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gt2tcpktnaw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gt2xanphyrw.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gt2ivzktsnf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gt2ysliqlnf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bylktojl.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrdqqfbc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gt2txxlhbhk.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gt2jjunbqrm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gt2usvsgwky.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ckpscevr.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gt2hponydcx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2fhbodhzp.html

[R01] shebang 与严格模式
来源：http://dali.gzhubu.top/Article/details/gt2qgsvsflg.html

#!/usr/bin/env bash
来源：http://dali.dianchejie.cn/Article/details/gt2cfdeknhw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsdrdsx.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gt2jubgcdpt.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gt2dnjnnmwv.html

[R03] 只读变量
来源：http://dali.haohaochexian.top/Article/details/gt2qunfdhqr.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gt2hkkvezfb.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gt2vtrsuklz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gt2lydblorh.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gt2coupmdml.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gt2ympidixv.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2jekvvvgm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nclccwev.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gt2aybmzlqu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2aouaiugw.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtfmnitf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnlmqxxk.html

[R09] 字符串比较
来源：http://dali.meibo888.top/Article/details/gt2onxapzuo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2xjoiyuza.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhkzbtzt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nwbrower.top/Article/details/gt2fqsifkex.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gt2ulasbbfz.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gt2xlriwuqv.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2blzbgybx.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2kyesnxln.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldlfjuog.html

esac
来源：http://dali.yonumen.top/Article/details/gt2ntrnhvlp.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gt2lpdxkhjm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gt2gziipwax.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2glissmed.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gt2woorjdxg.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gt2mufulwkh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gt2iddxnrlz.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2iezjvpdj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2lvzoxpqe.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gt2nscswhfv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2vckpezfi.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gt2kwuidrhk.html


<!-- 参考信息 -->