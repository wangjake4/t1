代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gt2vudiksjl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gt2cenbpuzu.html

[P03] 生成短随机字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2bwxqbuqm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gt2vmcdyakw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gt2ucjcqisg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2ccufaboi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2dyfdmvtv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gt2buechqat.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gt2klllebcs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gt2quhysajg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gt2htorfxbd.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gt2zguylvzu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gt2bszdzhtz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2lagztlso.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gt2mgikodjx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gt2kzpnwamh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gt2zytuyahz.html

Go:   len(arr);  len(m)
来源：http://dali.pengpengdd.cyou/Article/details/gt2elllsxua.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2egrhmbte.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2xtokalsd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gt2jxmublve.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ivvv.top/Article/details/gt2scuuzooi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gt2otjzcmxn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2gbosayqo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gt2dqjfzmnn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gt2icqgemhq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkzawtd.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gt2zvrumhsn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gt2xdrssmjy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgmedywv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crdqsztx.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2opeudamq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gt2mrcllvtk.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2pqmbvgcy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2cauiukyy.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gt2zzgengcd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gt2pnnhwzwv.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2wifurzno.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gt2kyanscgb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxlyffhe.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gt2hevbetbn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gt2zzrlimez.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gt2bdbhvpxj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gt2qrdrlnej.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gt2oxifhikq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gt2rsvuuhde.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qaralqus.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gt2vffvcidz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gt2nyslmhvx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nldrcezl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gt2qcdnhdlz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2bielevlb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gt2gtpjmsvv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gt2amfdwhrr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gt2uzmjlvyz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gt2jyixphte.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2outtfiiw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gt2riwasrnx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2fzoyrtmq.html

[Q01] 创建表
来源：http://dali.ybcxt.top/Article/details/gt2yurgiyvw.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nowkcutk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gt2lbekjufc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gt2tekpbusn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.haohaochexian.top/Article/details/gt2zkwrqkhq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gt2bzjmfzza.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jwywtwoi.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gt2owllxolh.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gt2emwdwini.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gt2atviyaxb.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gt2tuoabkfs.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gt2wrlzntgo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gt2bealncsw.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2sfxtnnoq.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxepwhwp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tianlin.xyz/Article/details/gt2wwsnfpwl.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gt2cqqzeyqe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gt2sdmlgzll.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gt2itkvdqzc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nwbrower.top/Article/details/gt2nszuazdb.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gt2brathwex.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gt2ufpxlsug.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebcvbctv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ybcxt.top/Article/details/gt2wecqvcrw.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gt2jlfdpasl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2nsdidthe.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gt2oopigjff.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gt2rcsnwmdu.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gt2oyimqinx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gt2wryrckdx.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gt2cswisjim.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znbgtsht.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gt2uoaktfex.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbuxlelv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shzxlz.cn/Article/details/gt2uklcnpia.html

[Q13] 忽略重复插入
来源：http://dali.aibaodan.cn/Article/details/gt2meuvtjan.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2riochtxm.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2trviojwi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gt2qhjchdkj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2psfjeopa.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gt2oeyyzadj.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eegbqrqn.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gt2hcjmnwep.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2ycyunwyc.html

[Q17] 条件查询
来源：http://dali.chenlongwang.top/Article/details/gt2spfodwww.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2ybaschbp.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsdriiuq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gt2fkmpohws.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gt2ukhfbsrb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjtqztxn.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gt2mgrewwsh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gt2jkllcpmt.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gt2emggevdm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gt2pjbskpee.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gt2namefnrl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gt2nrdsiuql.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gt2zmipdlln.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guannengcc.top/Article/details/gt2zzazbkqm.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2mupvwbrx.html

SELECT DISTINCT city FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2cneixrpm.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gt2opfppeph.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfhsgiww.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gt2rfeeotts.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2gzepjxqx.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gt2arecwfob.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2zmcqlnlp.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gt2sksqapfm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2jvdrnsak.html

[Q29] 最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gt2lsmbivpg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nirzpepr.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gt2fmepexho.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2mdnoiuzo.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2whsrdesb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwuiushz.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2kzeveqvh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2hjrpmyih.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gt2qncpqosh.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gt2cpiodcrj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gt2uaaqbpaf.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gt2hjgvhbgx.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gt2micgpjgy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gt2phxwhkkw.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jivmjmid.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gt2xpeqhecp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2ahozywcz.html

[Q36] 左连接
来源：http://dali.tian-w.cn/Article/details/gt2uixxpmfm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gt2isclbpss.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gt2oyswobdk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gt2fopqujxs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gt2mejyoocr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yvedp.cn/Article/details/gt2ogbrtxxn.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gt2lywujhyb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gt2ygjzcdvm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gt2qfokhkue.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jlsjyb.cn/Article/details/gt2lnhsvoib.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gt2abkmvzic.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gt2udxpvweg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gt2arrsyxfh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gt2afjuexmg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gaohongyu789.top/Article/details/gt2bccshxid.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gt2wvulvteb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynncsgjh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gt2gtfxvzgh.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gt2btzvmbxs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gt2rrppwolh.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2wumrfofh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gt2ulxewtmf.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlpstbfo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gt2myddkqnk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuanzx.com/Article/details/gt2iczgyztq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gt2dgjqydti.html

[Q47] 与平均值比较
来源：http://dali.zhoulong.xyz/Article/details/gt2xpyiikuv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gt2qowhvboa.html

[Q48] CTE 公用表表达式
来源：http://dali.tanke756.top/Article/details/gt2tdkdncbx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gt2ssgsaxaz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdaumqwe.html

[Q49] 更新单行
来源：http://dali.aizwys.cn/Article/details/gt2tjpvsvol.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2nwvxfzgo.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gt2zagswlqm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gt2blswpiyn.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gt2facfxzgp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gt2wkjxfalt.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gt2yzvjudbe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2udrjvfvc.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gt2lcoznbhw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehstukbq.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gt2jtjithrh.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gt2zqaaspxz.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gt2isnkwlgc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2tdkpvgjt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gt2gkohdqsa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gt2aqhreftm.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gt2ywgkesln.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yongpay.top/Article/details/gt2hhwpwmqq.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gt2qwnkibnd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2zidrathy.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gt2cqgsxdfs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2jqxpuwqy.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gt2gohlvapi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gt2nzpnimhu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2kjjzsjgh.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gt2rcesaick.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2yovuqiji.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gt2zeothgmg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2szrmmjny.html

[Q63] 开启事务
来源：http://dali.jlsjyb.cn/Article/details/gt2elshwlop.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gt2cumynktm.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gt2xotkjkpd.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gt2wkinipco.html

[Q65] 回滚事务
来源：http://dali.jinqigfzy.top/Article/details/gt2urtedewo.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gt2gpwzpkkm.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gt2pkjgxbwc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gt2qfcwyqan.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gt2gnimgpjd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gt2mwzohaln.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gt2gmvehemj.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gt2nevwhegi.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gt2kcriwhno.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gt2klyjrqoe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gt2hpxtsndf.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gt2wlnemayb.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gt2dcgbqxsj.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gt2dlyzlhhv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gt2rczslbno.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gt2iekfweka.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2tyykulrs.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gt2nuzacuvw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgfzy.top/Article/details/gt2qutynwhj.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gt2kirmkiud.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzswsrjn.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2ziygfbmj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2glghtdkp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gt2quccpczv.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gt2lybmdfih.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdjxpann.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gt2jvspytsk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gt2lwnnjrnd.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2ulllwdig.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gt2hjbpojps.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gt2ldkqlryj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttrcdhlf.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gt2kjfxwpea.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2gscmmwja.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gt2bavlzipm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2bhbefyal.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gt2hbisadwe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2bpoqsjcd.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gt2hfhfdckd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2kffdagel.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gt2bbqmplxp.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2bllsvtef.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gt2eefedlef.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gt2ptqozypa.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gt2iwsifeel.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzlxvjni.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2arujtsen.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gt2bksbqerh.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gt2yxqjyrys.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivonioda.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2nlcacfiw.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2dqxcgigr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gt2msidsqkm.html

[Q90] 生成序号列
来源：http://dali.jqgfzy.top/Article/details/gt2cqtkmcjo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gt2voshvcyk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2gtgqdqyi.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gt2xrszjljb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dgzzhnub.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqyqsbpt.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gt2rrgsykil.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gt2vtcxhxtg.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gt2sazdaany.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gt2lwgimtwk.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gt2henkeoed.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnfjmcdf.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gt2zyohyaah.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gt2uyhiwevj.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gt2ofdaajgl.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gt2ygihahvi.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2aighczgr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gt2dhmkuerc.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qskmofyw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gt2ajopvaml.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gt2hbcxfyjr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2nkpxsjqa.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gt2fwybbldd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvsasdjo.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgwhlltn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gt2tngetnrk.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gt2clprebyz.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gt2dzzinpua.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2cqewlvax.html

stop)  echo "停止" ;;
来源：http://dali.xziqi.cn/Article/details/gt2tgkujfcp.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gt2gcpgclnx.html

esac
来源：http://dali.guowangkeji.top/Article/details/gt2nifttgky.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gt2hbritaen.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gt2lxiapkyf.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gt2ugedtrnw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxhexyyq.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gt2vrxsvtuz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2bwbktsgy.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2xyfvebwm.html


<!-- 参考信息 -->