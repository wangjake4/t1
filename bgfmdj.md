代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gtqnxckwgo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtsatgzbjk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtaowwea.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yonumen.top/Article/details/gteoueseby.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gtljhzobny.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gthwmxbgsk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gtuvagetmo.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtwcnzpzlh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtaweheiwq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtaqxxnela.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtpuxzyhrb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtcwotxatq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gtalfocirx.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtspugqreq.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gtuvmepnir.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gtrhlacgad.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtgonliidx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gtvsnulelq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ppjwa.cn/Article/details/gtilphglzl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gtnzbjgjzu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtsuubttjn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gtosymycrk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gtpruymaoh.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gtegtcqofk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gtexmtaowu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gtoqobtuon.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sysykeji.top/Article/details/gtzctulwto.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtfsbypkbg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gtbgymghtc.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtoyogoijz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtmkwjsfao.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gtkktzuwgm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtexkfpjna.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtkwpjqqhd.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtfwjashdx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gtfbhmovsb.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtlmmgfyhj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtfxabuzew.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtixbmajen.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtjaffmlpq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqjyppmt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gtkyrsoyco.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtrujqmiqq.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryalqcce.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yvedp.cn/Article/details/gtffujzljh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gtkljdarfu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gtvtvegunz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtwgqmkgxz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gthjatkgnc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jlsjyb.cn/Article/details/gtofyszwbv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gtdmvnchoa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcvuiuib.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gteigfjjsi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwavdwhil.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttmshehsp.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gtknmantus.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gtgupffyci.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtcrobngix.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtwkpjsdje.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gtxtvdqcjx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gtzdonxypd.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtgqjpjtnd.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtscromyhb.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gthrdafxqs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtoqrhrhkv.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpelpigaa.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtlyzjppvg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gzhubu.top/Article/details/gtxbnftfqh.html

);
来源：http://dali.cashguo.top/Article/details/gtrjwfyqve.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gtmyaoggyj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtotbxqruc.html

[Q04] 修改列类型
来源：http://dali.cqqwz.cn/Article/details/gtbejbamdq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cqqwz.cn/Article/details/gtiikxjnpq.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gtkvbyzrlv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gtlzowlfdq.html

[Q06] 删除列
来源：http://dali.pengpengdd.cyou/Article/details/gtsziuksvk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gtwsuyborq.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gtwzzojnrn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gtmbrdtoxm.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gtfxrlhcha.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtlqsmpgsj.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtcukscpij.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtlifzmebn.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gttiuszyvj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtqmbjurfb.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gtbhbkguvi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvakurpr.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gttlojbreu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gtkykohhoq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gttxscpmwe.html

[Q13] 忽略重复插入
来源：http://dali.dianchejie.cn/Article/details/gtdyriwxeb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gtxudroiac.html

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gtnosrpvgv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gtakezpjzh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gtecmzersx.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtkfedzmhv.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gteskoebzc.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gtbobaxgod.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtqkzwkoqi.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gtgeifpvrm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gtabwqnzgx.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gtxwoewrdk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangshuangyany.cn/Article/details/gtdghqcprg.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gtlqoriobi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ehwqpu.com/Article/details/gtamhziqwc.html

[Q20] IN 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmhdbeua.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmupvpvzg.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtrfhzbloi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gtpmgsfets.html

[Q22] 排序
来源：http://dali.fengsongda.top/Article/details/gtlgecrpdh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xziqi.cn/Article/details/gtpndrthbe.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gtacvozqgy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gtlhbuagqd.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gtunbtdweq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtdqxmxfng.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtzaiizzln.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gtialksazm.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gtunnjwagg.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gtsfemzypi.html

[Q27] 条件计数
来源：http://dali.jinqigufen.top/Article/details/gtdsaktmbw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtsdbddzcq.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtpwuefhzq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gtjtdzissn.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gtontriogr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtkfyohsfx.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gtdtwozqay.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfijibne.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gtimpqxppf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gtgjimzaso.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtfpquylsr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtgpyvttof.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gthevspngq.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gtugjrdbrn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtgqppgqnf.html

[Q34] 每组取第一条
来源：http://dali.jqgufenzy.top/Article/details/gtjozsyygw.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gtofzxmgdb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gtxriscuqt.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gtklanefzk.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gtdjzvlkgj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtljrcgzow.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtsbinnqcn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtjndjwodf.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtvhwzcwfx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtcgfyekuj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtszjloqag.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gtjziomlmo.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gtmustzgfr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gzhubu.top/Article/details/gtzkyyxgpd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gtscqdsfug.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gtccalmilo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpsojnhd.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gttwbjapam.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gtemomuwhv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tanke756.top/Article/details/gtzpzfexlo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gtiuldqine.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxhinkjj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtagzehqdn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnpfgelz.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gtjyqrkicp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gtdmkpzmti.html

[Q44] IN 子查询
来源：http://dali.vqdsnc.cn/Article/details/gtbpiurfst.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtcpehvcue.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gtijrklhsy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtmcezrxme.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gtcssxbmau.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gththzfcnf.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gtssdwihqx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuanzhike.top/Article/details/gtogasncbj.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtcczinazb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gtjtfbavgk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtvgdludaf.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppihvxsf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtjturqyzp.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gtfwbtvkdz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gttrlmqckn.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gtfvcleydf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtlqujylgj.html

[Q52] 删除指定行
来源：http://dali.yvedp.cn/Article/details/gtiirdivis.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtnaratvvc.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gtowqwpcpr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gtmvzjfcgf.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gtbwmxxdcl.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtzawrwntm.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtrowajspp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtirbutcpv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gttxyuxzie.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtduebvywq.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gtnjuwlwdx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtjwkivnel.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtkjzeqcdw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtaoutmqyx.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gtagecrmxs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtcvgiweac.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gtogzjdjda.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gtfwlumqwd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedapyqmh.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqugtdcbc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtoxjveyko.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gtixxeclmi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtbxqvqood.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gtwdwahjwq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gtntnxtifj.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtybnipsqv.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtzlhgoxzr.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtkmqqchtl.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gthlgvmsaa.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtgqqieqdz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtbvbrymtb.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gtszotjsma.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xinyue.icu/Article/details/gtnypdljlx.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytepbkjj.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gtcjpmjbhk.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gtjmjuljkq.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gtljzopijp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtoemmeyng.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtwskhfqvd.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gtnjfpmqsz.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gtsugxylex.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gtlsfrnuwz.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gtqqbodddv.html

SHOW INDEX FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtqycqxbyd.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gtsjcsuwuk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhhvrjtt.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtqdtarkyy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gtrblgvzxe.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtxuneqecd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtuqdwndjg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtcfrpeeni.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtilesulnb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtjmjmlepl.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gtaelkkizq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtwaryoiqe.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gtcpinbsro.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gtsiqzffch.html

[Q79] 字符串拼接
来源：http://dali.cucudq.cn/Article/details/gtsxoeqpye.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangtech.top/Article/details/gtuizozlzu.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtjybktaqu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtpidxjvbd.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtblpiavyt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gtchrfeseq.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gtpsapklum.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtnfmdhxdo.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbveilzo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtenwfeivc.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gtzehqudcw.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtpunhiskc.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtfdqbbkur.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gtotexlfif.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gtvkiujirw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gtmptriddd.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtpjnxmacv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtzwrfsdov.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokhszqzy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtonynssva.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gtebkdaahk.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtikghqaab.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gtgyubzpvq.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtueadtpsv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gtdizrkqtn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgwkfzjjv.html

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gtxsqjqnta.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gteeevqnnt.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gtkizidzqr.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtwzrqfuhd.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtadvezccx.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gtifpjpyke.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gtazngzdmt.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gtzgxyrudh.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gtordfeqvv.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gtzukjvrjc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gttjrfrtnb.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gtmeukhcsa.html

name="${1:-default}"
来源：http://dali.gotoacloud.top/Article/details/gthcyjfnjz.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gtapbrtnwn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtjjbreybe.html

[R07] if 判断文件
来源：http://dali.haohaochexian.top/Article/details/gtukgiqoqm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtzmtcsezb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtzikbbepx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtqecqgzca.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtiviqkdgk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gtamuphibh.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtsgblbktx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtaibcmkvl.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtvhkmcior.html

case "$1" in
来源：http://dali.yonumen.top/Article/details/gtfuvfigfd.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtdeabjkrl.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtgzdmavvg.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gtqkwucfuu.html

esac
来源：http://dali.yonumen.top/Article/details/gtyiesitvj.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gtkhxedqyd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gtgssgsyvt.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gtmeetmumk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtnjrphpca.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gtucecnlpc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtgjrcjoqk.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtqulicusz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.iojbl.cn/Article/details/gtnptdlwxj.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gthuzdetec.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtibhddrxj.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gtibjttmxw.html


<!-- 参考信息 -->