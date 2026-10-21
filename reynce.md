代发 wailian999

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gtlrmevail.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gtqrtnjlzr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gtopzzkdrc.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtaeuijxnk.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtmcxfsqcv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gtsnudhumx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwzgonub.html

Ruby: SecureRandom.uuid
来源：http://dali.yj202588.top/Article/details/gtrikukyde.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gtfydhygix.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhengqikj.top/Article/details/gtoexdtfka.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gtxkzxihxj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gtmdfnwiet.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtafpioyxl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gtkerwxqpx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtbnikrxsx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gtiosarhvj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtlpkrcpas.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtlvozvznp.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gttyxyjyzy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gturyxbrsq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gtyulcebsg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtmpblklte.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtmdofyvqc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gtnsitzxfm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gtdkgyjpsw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtuvmtuubb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtmiduzjhe.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gtsifnapuk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gtzzexplmx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtvqcijawt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtggmzhluf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gtlegoxyav.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gthoejaevr.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gteqcjfrco.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtmwmelvfj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtwjkwapue.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gtkavugtgl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gturlozqir.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtqxiqpwfz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.kuanghao11.cn/Article/details/gthmhjizxt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtpbzamyja.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gtklkgrbny.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.meibo888.top/Article/details/gtjqbpiinv.html

Ruby: a == b
来源：http://dali.yangfankeji.com/Article/details/gtslxphbfi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gthmexwniy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gtobfbcccp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gtfwcqvyar.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gtjyskmzqj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtcmxaxfim.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtnrciqesg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtbjzehtqf.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdhwirgoj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gtrrsskcyq.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcdreses.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gtqlmhpqar.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gtyyborivx.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gtmzklgnlf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtsvsmuvce.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtehipaega.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtxpozlpjy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtuqdizuzs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gttldvevtr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gtebawwvoh.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtqeesaahr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbvodxgo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtnwftrxlm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gttqtfmwop.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtknqlnfmu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gtkpillfez.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtqpmcqrbz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtmmnfxsyg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.316326.xyz/Article/details/gtemfzslwc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfvtemey.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gtczjfhqup.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmcvlgqxt.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gtwtoyssey.html

CREATE TABLE users (
来源：http://dali.cdnleiting.top/Article/details/gtcjdmaals.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtuyqkstvw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtmvgaolop.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gtwtyidwak.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqodnsibl.html

);
来源：http://dali.daxiang520.top/Article/details/gtdqzhupwi.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gtuftraeuh.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gtvoorgnmp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtzcasvqiu.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtjqedbelv.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gtwroisrkl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gttbxnnmyw.html

);
来源：http://dali.andypj.xyz/Article/details/gtlpymmouu.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gtojxadadb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtrshpoerw.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtnwvkbejm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtosqrimsc.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gtwpqydbvw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gttmqqduqh.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtoekkngev.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gtiemausly.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gtowfsrhxe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtmzflwcfe.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gtrcskuabt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtpyrihbbh.html

[Q09] 创建唯一索引
来源：http://dali.yanxiufei.cn/Article/details/gtebvywugu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtquhjhukm.html

[Q10] 插入单行
来源：http://dali.nanxuanxn.top/Article/details/gtszhrmgiz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtstqzvmho.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gtbscukokp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtjldsqule.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gtmpyttfda.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gtbtqbajtc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gtwzhkurjf.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gtouflbhrf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gtojraorjs.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtexbuqqie.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gttoohaxtr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gtrntwgnhm.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gtdiszrptt.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtbufnjxxc.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtysfyaahm.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtzctopakb.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtusmrwzdv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gtejnqdota.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gtdqpzstue.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzejtrrhz.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gthviunbmz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtnqykkaiu.html

[Q20] IN 列表
来源：http://dali.cucudq.cn/Article/details/gtdghtyzjv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gtzxbymrum.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gtixsjypvn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtwlokrjam.html

[Q22] 排序
来源：http://dali.hfpthk.cn/Article/details/gtrjhxdkny.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtdukjjldp.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gtxphyoiym.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtvjkcprob.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gtdcydvuyj.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gtqvutqcmx.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gtozkdopjr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gtivoflajd.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gtpvllviyx.html

SELECT COUNT(*) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtzmwpemow.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gtwyguzejh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtfcihkbvw.html

[Q28] 求和与平均
来源：http://dali.pengpengdd.cyou/Article/details/gtyngecqho.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtnpuembju.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtvdypvtex.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtgkxvtzad.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gtoghyetin.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtwosqlzyr.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gtufmlvsyt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtntbwlmel.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gthzlzifwe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtafgwwbxi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daria6918.cn/Article/details/gtrfurztgq.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gtahsikesd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtkabssbya.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gtwglnhzjl.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gthvzamggu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtuolkbzbv.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtrrfmaatg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtxeqybhgr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtjhwbcscj.html

[Q36] 左连接
来源：http://dali.xylfe.cn/Article/details/gtslfwwmfj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtxesavtzq.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gticlqajzh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gtafpmxebk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gtgzyjttrl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gtbrulxtyo.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgfzy.top/Article/details/gtlyetiaha.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhongyouzk.top/Article/details/gtjuuenmfe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gtgdzouuir.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtktcmrvem.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtlgwnyfmm.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gtfuarknjg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxggypkmu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gthvlqztpk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyeazrmb.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gtonvemihv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gtmkdpcjnz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtuuvpuuiz.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtqjijhvci.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gtdbxrrbdj.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsijldrl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gtixghhghg.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gtnghdyjxg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtrkuwfonc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gtiflhhvyf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtozqgorbj.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gtclmgnnwh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gtixrkxriv.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gtmvgetbpc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gtlnjxvipk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sxryk.cn/Article/details/gttufqtvup.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtbepjepmr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtsbvfrhtn.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtehungfhm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gtzvgqnovr.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtzxabzrpr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gtifxqgyyr.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtrhlgizua.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtpmmbcybg.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtwizwkpqx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gtrdjnyvtv.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gteceufvet.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtycdrgwyl.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gtakxvbtsv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtdghmtrfl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gtgzvkjkuo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtlgydgjlz.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gtxgjtszvq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtfbrrxhgx.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gtqowwicxj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtwyvsxtod.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gtykbbrqal.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtcedlvrqe.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gteasitoiz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tianlin.xyz/Article/details/gtgnlbtxah.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtrhgdfznu.html

[Q61] 移动平均
来源：http://dali.smart0.xyz/Article/details/gtsuvhsqfk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtzoobimdd.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gtvyyumhjx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtdkjkxoes.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtjbuarslp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtpcugrynp.html

[Q64] 提交事务
来源：http://dali.jiagoushi.top/Article/details/gtlxmlnhpu.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gtrvovkdjy.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gtqhntmdaf.html

ROLLBACK;
来源：http://dali.9152youxi.cn/Article/details/gttadfocfo.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gtzhfpvmkl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gtcrenplxv.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gtmrkxsftr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtxotvvzhc.html

[Q68] 保存点
来源：http://dali.gotoacloud.top/Article/details/gthynmhnws.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtapcnnlgo.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gtihzawwep.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfosgxmho.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gtkyxpaetp.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gtkmqubhbo.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gtquibsren.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gtovjauiyo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gthevufeix.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gtwmyisnsf.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtqfopbfyv.html

[Q73] 查看表状态
来源：http://dali.zdqjudy.top/Article/details/gtesewrmxm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gtxnhtoggu.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gtzjesjwvq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gtlaszjupi.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtekufrzcw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtpuwwqfjx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pycfn.com/Article/details/gtzpdpsrqz.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gtetftgoco.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ehwqpu.com/Article/details/gtyapmyrre.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtiasmtvov.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gtqyvxpmcd.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtobreciqm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gtwtqpgtyw.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gtycmwxlyg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gtgvnjzuuy.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gtncbolsyx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtwdaugiqc.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtwlwzrnfs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtdbegwubj.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gtxbsnzayv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gttylflvll.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtdfsjtrgk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtsyjsnift.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtbuhmzpwa.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtqvczjxpg.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtdlqdtpnp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gtyzcqlasb.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtzliwimji.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guannengcc.top/Article/details/gtqpdefnwi.html

[Q87] JSON 字段做条件
来源：http://dali.nanxuanxn.top/Article/details/gtpwphnpkz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gtkcwfpnxm.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtveuoehqz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtgtjucbsr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudspawag.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gtoispdrdy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtaqualvcd.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gtdhkwniib.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gtxgarhrgl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtnabdoluo.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtczrughfv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmraajrji.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gtsygxflts.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gtczmowtjg.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtnftrvwvf.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gtcwlqjfww.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gtcqypunbt.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gtmpgltuga.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gtmsgxblha.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gtrxhrtrzx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenlongwang.top/Article/details/gtzxpusvnc.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gtlgsyjcpl.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtghyoehhe.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtdgidsfaz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtwzzzrmvx.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtkdspgbql.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtwqbpdmbl.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gtgojsfkpl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gtfglkoyue.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtbimcwaad.html


<!-- 参考信息 -->