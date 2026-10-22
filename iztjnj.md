代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gtetijqvhm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtavmztbqg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gtltliawnz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtecjuuwtn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtuoorzmvq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yanxiufei.cn/Article/details/gtuetdwhha.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtfzotnral.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gtbtgtovlf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtyngnvsqi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.smart0.xyz/Article/details/gtxvkfntmw.html

[P03] 生成短随机字符串
来源：http://dali.yongpay.top/Article/details/gtcfkrjkle.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gtzrjbpgtt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gthjriwjqu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtaxbaiihy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtmuetwcuo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtzynbizjk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gtkqrzymrd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gtqhiumbrl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gtqianmztk.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gtjdsijlec.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtjitrodcw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtjgxpvzjz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhitagkl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtqikrfbxc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtvnbbqufm.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtbkswrcpc.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtziioicyh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtnetnyokh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gtosuiexff.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gtwdfpdhkf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gtnlvepjwa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtutefjtvh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtojuqkfqb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gttazoxmxx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtdhrudoio.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtavtotsbm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gtixfvnsdx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gtepbqrena.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtralujsnv.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gtkrfrsjja.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gtygodvmqq.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtbsyuzruu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtkonytdwg.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gteyugztyz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtghkycdpo.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtozvouasa.html

[P07] 防抖与节流
来源：http://dali.ivvv.top/Article/details/gtesjaaabe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttececwsl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtzdfbmizr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtfvgqofvl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtnsoqiauy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gtdcmzdirk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gtawnaamzp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuaiqwis.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gthkpowekb.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gtokjncpoy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtgnuwwand.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gtomdzypba.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gtcmccggjv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtpwwakiuq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gttzuljxag.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdofagyy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gtxckuidce.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gtgcainedh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtzhbdjtgr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtlxkeexks.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqygzoenc.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gtgrkbjluz.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtfagasxlf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtxsbddeyk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtbwytwgzi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.316326.xyz/Article/details/gtwfliftid.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gtheasnmpw.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtkynvkvpn.html

[Q02] 创建带外键的表
来源：http://dali.fzhhl.top/Article/details/gtewcsbujq.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gtlqowvlor.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gtrmvjwhzt.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtsdkfedew.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gtwirgynjl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.316326.xyz/Article/details/gtjsmgoyep.html

);
来源：http://dali.zdqjudy.top/Article/details/gtrttdxpfn.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gthgmwtrqk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gthvcsrxlv.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtxeumqzck.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtzxnllfoi.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gtvbaufxie.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pengpengdd.cyou/Article/details/gtapzijtjv.html

[Q06] 删除列
来源：http://dali.daria6918.cn/Article/details/gtjqrpzlnp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuetiantiany.cn/Article/details/gtewioywgw.html

[Q07] 删除表
来源：http://dali.smart0.xyz/Article/details/gtvrmvczcg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gtjtngrivq.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gtwdyoazww.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpefllnx.html

[Q09] 创建唯一索引
来源：http://dali.redwolf501.top/Article/details/gtbtaphglj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtwolenioj.html

[Q10] 插入单行
来源：http://dali.guannengcc.top/Article/details/gtptzvuhxe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtofqznsyf.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gtjrlhndgl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtvrejwmli.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzxmfaug.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gtxodwarey.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjodagdby.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gtmbkfcuhh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtvvrbauep.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gtvibnqvsx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gteanynyqj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shuidangran.top/Article/details/gttygcfzzi.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gtgpbhtnav.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gtgwueufre.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gtiplcntfq.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gtednkwuiq.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gtcbvurabc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gtuiwzstpf.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gtoxzcqmnp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gttvetpiee.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gtapoxcmhg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gtjikzhpqa.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtkotkyiid.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gttvvrjgsp.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gtfuocawgn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gtcwfievcx.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gtwllvtihh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gttmzbzkqc.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqeuodly.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtrzmtbxqi.html

[Q24] 去重
来源：http://dali.jinqigufen.top/Article/details/gtifgssnzn.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gtcnglrvid.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gtqwfwrwad.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtkrfnawgm.html

[Q26] 计数
来源：http://dali.cdnleiting.top/Article/details/gtzfopzfop.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gtcfkcsqjy.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gthjhuzicj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobfoqmlu.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gtnbqumrmx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gthrshtcjx.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gtfwzvhpzt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtrkilfivc.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gtcjtyoqwc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohlprury.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gthwiljsyu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gtimyauukc.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtywresxpx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtqyebjsor.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gtbecajjul.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gtqgzzbcqk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gtdzlsxgtp.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtkembfwjk.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gtfplofmwm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gtwntmyjyt.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtytupcxcw.html

[Q35] 内连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtajqvfvbq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtowecftmc.html

[Q36] 左连接
来源：http://dali.jinqigfzy.top/Article/details/gtnqnsyipk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtmzgufkud.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gtksvlshmz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtycgxgxwf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gtfczezozt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtbgdyenwo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtuervrfjo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gtmibuzgzz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtwemuinul.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gttobkylfp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gtivksftbg.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gtwjawztxg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gtyxbhypgz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zycfv.cn/Article/details/gtzkpwgbvi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtnkphtqys.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gtpyhtpqwm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gtikimfgex.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtehdqennc.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gtjwkynmlm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtxajcmvet.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtwmvrepzc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gtiqwhprck.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gtfizjxrkk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtssnuqvrs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gtcijgcdre.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtbkitfyap.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtuewoodlt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtqvbstohs.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gtjgpvglxz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gtopubeegc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhiwuduotai.top/Article/details/gthvuvfcrr.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gthfnlrziz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtmsaqutch.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gtbufspvtj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtztuclbtg.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gtvvekcvup.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gtaieqimkj.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gtdguqmona.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrttqqjf.html

[Q53] 按条件删除
来源：http://dali.svipenyu.cn/Article/details/gtlxcwomgz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtbuhmpsia.html

[Q54] 清空表
来源：http://dali.xuanzx.com/Article/details/gthvfrpaax.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gtdtapxews.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtpaixwvdt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtyaktuqxs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtxsadizea.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gttrermmus.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtlqgjzswa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtnppihjgn.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gtfgyibslf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtobpckuzu.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gtaagrivam.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtttqtqbua.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtcxgrchqz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gthsqttqgf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtjpwqctvm.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gtjikfnokv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtjddlzxit.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gtdrusgiea.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtjrqohkdw.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlcggbzm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtbkjpkede.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gthgbkujyf.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtqsepypgu.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gtmivaksmb.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtuhmeenql.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gtomqbrmkk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xylfe.cn/Article/details/gtbyxwfnpf.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gtmhcuejns.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtmtnmulbb.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gtnmyrqarl.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtqlvcqswb.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtmxaswlqi.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gtkzrvnkpx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtugqvwvyv.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtpnpahdsq.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gtqliadnti.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gtogrgpvmj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gtopxqorjv.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gtzwgvkuwz.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtpmsyxhae.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gtrgevfrxm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gtcmzcksnj.html

[Q74] 强制使用索引
来源：http://dali.cucudq.cn/Article/details/gtrufxtjfh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gtvcsfiffa.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtitkpwkqp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtrtbkgbpl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtcwnpvhph.html

[Q76] 按天统计
来源：http://dali.shzxlz.cn/Article/details/gtkpjwaojb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gtpxqslxkp.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtcfoiigqt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtvczfrzor.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtglkdxlbt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gtltgqwlgr.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gthijigwqf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gthlfnstov.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtmclgeboe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtyungtdyh.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gteahoxbcf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtorozouwj.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gtzifcaatu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzazcuwn.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtxunfvxqf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtuqzggkzu.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtbveacggp.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtemszjugw.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gtioabhjat.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcqozqmm.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gtkrcwuwll.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuetiantiany.cn/Article/details/gtxgavtvro.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtftuuwhfc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gtprfcepxm.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gtsqhsvbns.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcfxztdo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtkmnjzabb.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtsjfiivjb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gtvbpdmpqx.html

[Q90] 生成序号列
来源：http://dali.meibo888.top/Article/details/gthjuxovit.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gtdwvcfcsv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsuonarxv.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gttilifjbl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssbmhadd.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtjiynkexp.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gtjlyjgrlr.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtitdmqpux.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gtacgxtbfe.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gtygyjwyme.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtljiftkww.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gtktvxmqcq.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtwicofyfx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gtcesybbeu.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gtdhdheajl.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtmgfebjkm.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtailectue.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiygmecru.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gteguifizd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehefhjpt.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gtyqaowcfo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtqqlckfoe.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtublesnup.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtxgazlfns.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gtlglnpxss.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gtclczthqh.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gtmwtrvteu.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gtkftbvtav.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtjxmyruln.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gtufndnjma.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtkafecrxo.html


<!-- 参考信息 -->