代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gthsartqqx.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtbkjhwqgf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gtykkgehbf.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtixuqwmpb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtdwiexobn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gtmbfflgmd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gtuqljktwk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtkawqssmm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gttlwmqepc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gtoaovlbvm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtqkrhtese.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlgzsydb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtuvqkbxxq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtdqvfappc.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtidoojiga.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gtwygrftme.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gtcuenjnla.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtuwhjvwlr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtndvgupgg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gtvhlzrfyj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hongshengwenyu.top/Article/details/gtsdfrhwan.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtspuybnnk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gtuzretlay.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gtlzetxmcb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.0kj1m.cn/Article/details/gtohtdeknv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobcminbd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtqrsslixr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtzyrfpfjg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtxfvfvxwp.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gtpqbczdmb.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtvipusutp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtlhbclqcw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yvedp.cn/Article/details/gtzufebykb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gtpivqxtne.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gtdcrciccs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gtcgccxtau.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtallncfsm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gtpbbvtzyo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtckwyauka.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtjmotyvtc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gthwuudlxr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gteqzdpzxk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkwpheqb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmgllbit.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtboztprkr.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtmgcbonjv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtyoctzanr.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gtbtuhcyzn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnqzz.top/Article/details/gtkbmbcbse.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gttehextej.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gtjknsaren.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtuaxtyoyb.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gtzsjjowsi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtjvlgmdxj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtfvxzpmyl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gthieapndw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gtszbzmeld.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gtoekbinqc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gtpmpcojsd.html

[P08] 处理浮点精度问题
来源：http://dali.hammf.cn/Article/details/gtewkrddiw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gtlpkuglso.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gtfeuvwkkr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gthhhsvcfx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtclatkdhh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdohnuoah.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gtjakjvzzv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gtttkkfnrx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gtwpqhrmja.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxgmropzd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fengsongda.top/Article/details/gtzcezpocr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqfigisho.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gtropwobkw.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gtuzefdjsi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfstwhxs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtenihoqjp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtorlquqjy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.0kj1m.cn/Article/details/gtjdpaipkt.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtibcwwbtk.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gtyafjulza.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gtlxyvxunf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtzinczhju.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtzbenafbx.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gtzpvmkpgt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gtrqogkbat.html

);
来源：http://dali.xylfe.cn/Article/details/gtuyuehiue.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtgfamiuxm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtbkselohr.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtgzrztkkr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gtadanqeit.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gtvzndjzhg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.9152youxi.cn/Article/details/gtyxsyvppn.html

[Q06] 删除列
来源：http://dali.iojbl.cn/Article/details/gteyyqraww.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gtkkakkldw.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gtorilkqbp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gtmbqhhhxz.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtqlzkynqr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtyaitxauu.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtktkigpgl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtahapvzvb.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtxdpjhblh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwroooit.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gteqhbpxvr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gtksqzwjit.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtntyhpmpn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gtsssutwqb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gtavxnxkcj.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtmqykelyw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtqzmefiaj.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtaeymwkbd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmlunxqu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gtysegansy.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gtbycdfsjl.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmqqzwco.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtighzlkss.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gtfndxzqsg.html

[Q17] 条件查询
来源：http://dali.shanyushiyangtech.top/Article/details/gteygnzyti.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gtojnrntht.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gtnsudfzhg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuytzrbde.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtbbynkzfd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtzilmakda.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtmwrbdpnr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gtpncmvcff.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gtmuouzrfa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gtcoaidexw.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gtvrkszhxy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtgxswbafc.html

[Q23] 分页
来源：http://dali.zhiwuduotai.top/Article/details/gtuvsqkmjo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gtimlodiwp.html

[Q24] 去重
来源：http://dali.sxryk.cn/Article/details/gtztotoepq.html

SELECT DISTINCT city FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtqmaepusc.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gtinqxnthy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gtmasgdbsy.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gtpwopgvmb.html

SELECT COUNT(*) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtwsssntju.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gtvntcphff.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtzqqruyjw.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtltstpjba.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtbdkvjksj.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtinorebrp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtgvcqtoqc.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gtdgrdkjpw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gthxendbuo.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gtubydhywq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gtmiwvpepo.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gttaereozg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gthunzxazz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aibaodan.cn/Article/details/gtbblfexkc.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gtscbssoqj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gtdarjkcjb.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gtnbrhpyym.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtcsjzhyaa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gtlqwshmnw.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gtfplmmxwz.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gtyfyvxuyk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtvdubneqa.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gtsokylhba.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtyxtehktk.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtmghxjbww.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gtldnhrxil.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gtzihtlcwx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuudtffa.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gtxgpmbpil.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gtsniqmcda.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gtlpnffmhf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gtgixgftxw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gtbtvnrnbl.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtqrnuktso.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xinyue.icu/Article/details/gtcjofwzrp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gtognnfgpu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtitbvfewz.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gtahcmweag.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtgbpsjbzp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtjtbieyyb.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gtmpwrvlti.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gtdmsizesr.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gthdqjntmz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtbvoroamv.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtvafwikpl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gthjtvtcqu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gtlcnvwmzl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtpjjfumga.html

[Q47] 与平均值比较
来源：http://dali.xuanzx.com/Article/details/gtmutxaxym.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gtsalyxjvg.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtsbqcaobj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtujsudwis.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gtnbiwagtt.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gtpygmdkjk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtxbykiljf.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gtszreucix.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gthmolubrl.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gtzwhyzkak.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtkuyxxkvq.html

[Q52] 删除指定行
来源：http://dali.ivvv.top/Article/details/gtkexmnbxl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxlewmdr.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gtppsmeqcx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtscphswwp.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gtoedlekkk.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtpcpahffd.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gtahlncluf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gtgmorzabo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hywenlv.cn/Article/details/gtywhflpak.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtoelfccuh.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gtssaqybdj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtgzgusxhd.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtpjodpgzo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtpwptqiih.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtvegxonuv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtymjwqzkf.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtrrmiijeq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gtuxbwxcak.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtgjjbspdf.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gtsyyogqop.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtfzlxzpbo.html

[Q62] 分组占比
来源：http://dali.meibo888.top/Article/details/gtbeqbivkb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtfcpzvivk.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqkwgmza.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtidrhnbvz.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtimtfayfm.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtcvyfvvqq.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtqrhhkyjs.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gtwdmgacrn.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtnwlhpbug.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gthvbyygcs.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gtqfbhatwy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdciwoupx.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gtlrgqnzbw.html

SAVEPOINT sp1;
来源：http://dali.gotoacloud.top/Article/details/gtmkrhoerb.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gthhugsyys.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtiekshbhr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gtigpuwraw.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gtvvsmojbo.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gtsbaqiugz.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gtycosazjn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gteerwdgak.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gtyheaktrw.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtcrbjptdq.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtaboszqsk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtasxdqbtu.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gtnoljjdrb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gthropcups.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtgcgliyig.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtsgzmgnbg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gtgsxwblfs.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gtmyxsjijs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gtctbaekgq.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gtorljnulu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gtfjlryltv.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtlvouutwf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gtuvubwvph.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtjcfanaqh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtrygcvfuj.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtrpcqgxrs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gtsefiinon.html

[Q81] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtpuwoqsob.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvqlyufpt.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gtsduzdrqv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtgnthkuym.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtllngtykw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtjrywswgf.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gteqmmrfrb.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtdwslzexo.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gthmjopvmp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsjqfuvq.html

[Q86] 读取 JSON 字段
来源：http://dali.daria6918.cn/Article/details/gtkxjxvmoz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtrlexmynv.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gtybjtgmud.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gtiicxuteg.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gtqmlpmitq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gtygirllkh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtbywhwnfb.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gttpqgbmal.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.c1oappe.top/Article/details/gtudypaqvb.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtjragmpfu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gtytsfbgkm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxkvzgwpp.html

R. Bash 专题
来源：http://dali.andypj.xyz/Article/details/gtjvxyigfc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsofcdgds.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhrvhvtg.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtnsctiylm.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtkqhiirfi.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gtliabobnl.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtrmwozxft.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gthqjyvjam.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtpehsjmal.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnnvmayc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fzhhl.top/Article/details/gthwpscdsa.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtmxaexfvd.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtocvhyakg.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtnigmahbs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtfbbukocd.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtrziscgfb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gttynozlxn.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtpotwulef.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gttywiiozm.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtsxssywlj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtjcbligoo.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqjfrskg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.kuanghao11.cn/Article/details/gturtucplq.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtzidsnsnc.html


<!-- 参考信息 -->