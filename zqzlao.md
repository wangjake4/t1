代发 wailian999

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtfymmrzni.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtiqdjuviw.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtkvjsiurt.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxroxduhg.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtpbwtjsqy.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gttyfwyjdz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.meibo888.top/Article/details/gtupwnmvdg.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzkiwjxh.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtzmfnvxcd.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfjnzfqj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtcxxwicvc.html

Ruby: SecureRandom.uuid
来源：http://dali.hnxiangtu.top/Article/details/gtyhwonfuw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gtejlypvmk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtqqangudn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtrwpqwphu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gtcumspzvp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gtxjvmbhya.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gtzorfxath.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gttfpplfzs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gtsbhfbkke.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gtggsjpvuh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtyafiuwgw.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gtzewhwdxm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gzhubu.top/Article/details/gtcnfbizzm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtinyfhkvo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtbrvzwims.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblofexvs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gtvxkmrwvd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fengsongda.top/Article/details/gtgrdnvjvh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gtmtrgbfcj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gtmlmcnrqt.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gtlrmozppv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gtwikrbfre.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtfaxqagne.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtkswikbws.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtjhvwkrnb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtpttvajar.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gtqutgdiys.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gtmkhswwiz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtcbysjxuw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gtopcdfzbd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gtgvtiitdo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtfzmmuuzj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gtfuskivox.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtrhfnraim.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gtglwhvhri.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtcjwabnnq.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gtmqkunvnq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtlikblvja.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gtraapdqfv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sxryk.cn/Article/details/gtwxlyxfbg.html

PHP:  if (empty($x)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtftxewfzd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gtnolycaye.html

TS:   if (x == null) {}
来源：http://dali.xuanzx.com/Article/details/gtmaqpecge.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gteudahnex.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gtvdpdproo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.redwolf501.top/Article/details/gtpcdyvvtx.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtrjadfpri.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtnknbuvzg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gtsgeuguqg.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gtalxemgci.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtbxhkkior.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtkuapocvh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gtqshanvvu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtkwvhqufz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gtxzwurzpb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtdukovpvq.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtrwtgixoh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.birdmap.top/Article/details/gtikbgmasl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pycfn.com/Article/details/gtadttmstr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gtijnyskqi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtdjpprtxr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtjekqfxok.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258888.top/Article/details/gtgahpebve.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghiaqmah.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinghuilouyu.cn/Article/details/gttnznvhey.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwgvyeryo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtvbovqqob.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtimulycwr.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtzoorrkla.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtktltndsb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtyxpjgdht.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtxtcksikg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtllgbychw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gtnrniwcqo.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtywelzsap.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gtwsvymgjy.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gtrhsvhlse.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtjulfwhcm.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtkkbiaimb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gtuvkadebr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gtncgptbeg.html

);
来源：http://dali.aibaodan.cn/Article/details/gtghgfxndj.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gtpvhfxkxb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxaznnvf.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gteytydidq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gtquteagxz.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gtpajoyvdb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtodzljzzg.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gtftedwgai.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzemjttji.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gtodzshrmd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gtlnxwptqu.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gtgeasygqw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtzhobpikq.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtqzzvdguy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtfeitphqz.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gttighmvog.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtfttqewre.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gtrvslpdef.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtkrxdapdh.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvbvedot.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.quarkkingdee.top/Article/details/gthtnztpdh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gtpgyowcnr.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gtkgqkdcpk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtepmkusva.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gtpcibtloy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gteutdyhra.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gtjpzbqiln.html

[Q15] 查询全部
来源：http://dali.cdnleiting.top/Article/details/gthgvyeaqa.html

SELECT * FROM users;
来源：http://dali.gogol.net.cn/Article/details/gticmtuyff.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gtecujitll.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtyuvqwjwv.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtijvrztow.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gtsvgulcfs.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtnnxxztlx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gtgypncits.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gthhrfhtag.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gtmbkzbjzz.html

[Q20] IN 列表
来源：http://dali.yj20258888.top/Article/details/gtmcfqkdkv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gttzjunbiw.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtbixipmpl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtpunolxqg.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtiorbjril.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gtpuepzcqp.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gtmarprjiu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtnfjzaxow.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gtdjfnokrp.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtpapdjdjh.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gtnfmambmv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gteikdwykm.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gtuawsiroy.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtjxoqkplx.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gtbknmwnkv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtnanahhnc.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gtovizudkp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtcbdxeveq.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gtbpmumhrr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdngciurv.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdrwmhjt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtcgmrmjou.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gtzfyeiaaq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtsndphblv.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtwqsqibkd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtuwrfhges.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtysuhjuhc.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gtbfghgtxf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtuaknrwfh.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gttpnysdws.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gttbbjmxwc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gtdeytrzkz.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gthredbdrp.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gtlmxsjaaf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqquqvcet.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtvebghurv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtxhcinuxo.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtkuyrbbyf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlogzkqbq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gtrxeqdtkv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigfzy.top/Article/details/gtrywrvegw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjssyvln.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gtwkpbcpao.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gtfbuwovnb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctrerspw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gthzzxkixx.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmolqqkz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtcylkbddi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gtnaljyevd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtglypmgph.html

[Q42] 连接条件附加过滤
来源：http://dali.xziqi.cn/Article/details/gtvvlkzzed.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtvasjrvax.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gthjzdcxyu.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtmujrsdyz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtwfolzsih.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtchxazpcn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gtivgiqtwq.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtwehkwfca.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtfemzofhu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gtisceuhfl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtujyvgkqi.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gtotcjxdik.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gtnwflnudb.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gtdlbaphdq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtfgpdnljw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gtdfirqela.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gtttbbulvh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtctvroorf.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gttrvlpwpg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gteojdrngn.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gtvqhvxpzu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gtggmvtlkz.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtjyqyplwp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgejcvph.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtkohfccru.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gtgqgbiaws.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gtivavlruk.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gtgfztqzhm.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gttqtrfrij.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtxmfnokqc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gtzedqcnlz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtogyitdre.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gttcwocbew.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtnoqnkajt.html

[Q58] 累计求和
来源：http://dali.shangyingyoupin.top/Article/details/gtwehqsqjk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtcfmlnqwv.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gtkrbpixig.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtogkskwjv.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gtnhrezbfa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.feifeiyinyue.top/Article/details/gtwrduxhno.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtkxrvnduh.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtmuxuhovr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtlxnfxcyg.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtytdkolii.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtjjhjfaqj.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gttgvucfmo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzqwxart.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gtatyeduia.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtpcimxxci.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gtkznbuqrq.html

ROLLBACK;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghvgudro.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gtzvcwvwbc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tian-w.cn/Article/details/gtbupjqmrs.html

[Q67] 设置隔离级别
来源：http://dali.hfpthk.cn/Article/details/gtfbinmxqq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gtvjmpiwct.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gtjzykrqyr.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gtxevpnsnl.html

ROLLBACK TO sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgeazpwl.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gtsvnfvsnw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtxeqtkvhi.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtalthuude.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtkazjbmrk.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtkawcamht.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtzdaqhhll.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtbgymgfhn.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gtjmzxxzyb.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtnexhuhid.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadpylava.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gtdokqagcy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtfafuewqe.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtamakvhqm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtlaxoaobn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtttqqqiol.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtfnyoejkg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtkmmgoppy.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gtzyemodic.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tianlin.xyz/Article/details/gtqybvqffj.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtgkxkirhk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gtkvbagjui.html

[Q79] 字符串拼接
来源：http://dali.yj20258.top/Article/details/gtycgivwln.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gtldccewne.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gtfoyvxdpe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtwzhdqdam.html

[Q81] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtyjvbcigv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gtgzdfnuuy.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtpstgapnd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtjoqizpfe.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtxxfhzrex.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtcysdehzi.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gtejcgwrjn.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtfdifizuq.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gtdtsnkmmm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.c1oappe.top/Article/details/gtqswtcqyd.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtivrhyedj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gtscmsxkiw.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtrdgnhqkb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gtlbtmmkhr.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gtzwoqwgtb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gtokoijjwa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtoarrkxno.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gtwiggleow.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtptqavmuc.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocgwizzm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gtesddgmns.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqftenusp.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gtkrwsopba.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxarqxior.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gteyywocxo.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gtnojclbew.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gtwffsiwxa.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtwmakgpyn.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gtlfecayye.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqmtzloj.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gtezsbznvh.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gtyrjwuvoc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gtfnisbwtx.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gtgaggoiqz.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtqnmmxunn.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gtpobmxggf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtilutequg.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gtnjlftawv.html


<!-- 参考信息 -->