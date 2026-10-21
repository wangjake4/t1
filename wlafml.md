代发 wailian999

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtswthkhnn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gtcdworjbm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gtgqcgptgg.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtezjplaxh.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtviwmdwee.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gtciptgdxi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtsnkpurxq.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gtyxtehvur.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gtxztyynnm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthmtxwjwn.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtfjxkbwdm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcentjznz.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoxdpqhy.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gtlcxvpoph.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtfdcrkajm.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtcvbhirnl.html

TS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtnqoucxyn.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gthsqpytgb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gtpxekpcwg.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gtozpabqcn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gotoacloud.top/Article/details/gtcqfgyjfy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gtlvfksync.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gtocybsztz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gtgvpbgrkk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gttfwjyzrh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gtjcgpqdwo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtvazdxlyl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtwqhqctaj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gtbmkobgko.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtxbjshptq.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gthnfkgbwc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gtmdsduiaw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtpnajemoa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtwhkfraea.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gthfzulnsj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gtpgbsbsxl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gtwikxxihf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtewxfbybw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cqqwz.cn/Article/details/gtvsncolpd.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gtrrocylvl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gtknrxebrv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtwcqdfgfm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtnzwmybpz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gttdxlekab.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtfwrpvsct.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gtcdwuqaqc.html

Ruby: x.length;  x.size
来源：http://dali.gaohongyu789.top/Article/details/gtqloujxwb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtirehjzyy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtvwinpmsz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzeutpev.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtgxjkcakq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gtxnbhgudf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtszmmbxvo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cqqwz.cn/Article/details/gtcksezjyu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgxntkgd.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gtorgszdfk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtaiekmduc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtoswnexob.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtsdezkgvq.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtzaqppfbt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gtxrilisgr.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gtbqttquek.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtmlejrhzb.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gtstntyfbc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gtubizhwqs.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtkctlfrjk.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gteocsvnww.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtncimqejl.html

PHP:  // 手写时间戳比较
来源：http://dali.bjfxy.top/Article/details/gtfmwbutoi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtkwhnvxki.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtjfsijsro.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gttvagcxzw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gtupuqwzxh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtwjmzuaen.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gtqpcavsoy.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gtwrindufo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gtxxlxncno.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gttzdoyrea.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtwdwlnilr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtqazcgwla.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hfpthk.cn/Article/details/gtkpaunheo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.bjfxy.top/Article/details/gtpjqretal.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hysaishi.cn/Article/details/gtxhdxvhty.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtrveuwcli.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkiuwtfjf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tianlin.xyz/Article/details/gtbeseuivy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbelolpn.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gtslithdmf.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gtoqkushmn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtvzjhplej.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwjutaqk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xziqi.cn/Article/details/gtbvhqogyj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrttxjrjb.html

);
来源：http://dali.wangdashe.top/Article/details/gtpjpxxkgv.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtfmtcsznr.html

CREATE TABLE orders (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzklsrnut.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtkrypwqts.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gttexqoccs.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gtfcxsqeoo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pycfn.com/Article/details/gtryduvcze.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtfznzoknk.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtrpdefusd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfghhphpy.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtkheddqjw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gtdbivshat.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtbyogbbtn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tianlin.xyz/Article/details/gtoisyjcnv.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gthsyeijah.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gtcdmryozu.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gtkblidxrh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gtivizpyiw.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtkhhaccxj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtvifykgbi.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gtyjkwzugw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtwkegfuyb.html

[Q10] 插入单行
来源：http://dali.nanxuanxn.top/Article/details/gtsbcadukx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ivvv.top/Article/details/gtpoiestrt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gtzlnlyjgy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtmltjoikf.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gtnrswcqns.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cucudq.cn/Article/details/gtohklmqvv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gtrhjxaobb.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gtfewajrvw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtxbmjfbgu.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gtwcqjewat.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gtbbobqrts.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtolxcamve.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gttmpdgrul.html

SELECT * FROM users;
来源：http://dali.sysykeji.top/Article/details/gtinnwiaax.html

[Q16] 查询指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtwimnbwky.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtrpkgyjte.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gtkpklmcqj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gtaptdmuam.html

[Q18] 模糊匹配
来源：http://dali.birdmap.top/Article/details/gtuketpxfb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gtjetvlpjf.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtgivkcskw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gtdeolkatw.html

[Q20] IN 列表
来源：http://dali.hysaishi.cn/Article/details/gtaiiystct.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtodmdkolm.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gtuweghosl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gtkutsgeyp.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gtrhbndtqm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtlbcuykmt.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtkpjwufzq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gtymmcmima.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtjouqbjxh.html

SELECT DISTINCT city FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrpeomya.html

[Q25] 只取前 N 条
来源：http://dali.svipenyu.cn/Article/details/gtqpwyukhw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.andypj.xyz/Article/details/gtjdmwsnkb.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gtygdmgzpq.html

SELECT COUNT(*) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtfsvcptuh.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gtqdpnpwpq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtzgovhduo.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gtaqxmatoj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtwpodnhxk.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtczkulosm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtgnfctgmr.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gtiadetsgg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtnfjtnptk.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtrzqyqipi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pycfn.com/Article/details/gtyqzegizr.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtbgvdkvyg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtfjtgcsqc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gtfivrsmem.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtnxbfakbi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gtreccbzwi.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gtzdoiayhf.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtihvficou.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtqdwnpveh.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gtuphzqmym.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtfgwgpmmb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtktwlyjup.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gthernxljt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtysxvvbah.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtrzvxasrc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gtzlzbtjgj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtnjukzsav.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gtdmgcuxyw.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gtbkajgayo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zycfv.cn/Article/details/gtkwgxbyvc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gtesycvoxx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gtqhhwmubq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gtlmummjzp.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gtgofbsqll.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dashuyun.cn/Article/details/gtwtzdijld.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gttpyunpty.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gtvzmulors.html

[Q42] 连接条件附加过滤
来源：http://dali.shuidangran.top/Article/details/gtjgmkjquc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gthvoiofsq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gtupbpkyrw.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gtsxgjjstm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gtfvstvaxm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gtbxylmoic.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfcmvwtv.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gtdqpzypzu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtczdzmilr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gtwnwyqsys.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtmcbdgfeh.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gtgvlphpfu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gtodipwuzb.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtsrdbpbkn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gtckjuorys.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbszumrw.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gttdrzuvuh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtjkbpdzef.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gtorwdtcyv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtfeugtchn.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gtvcsadryw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtblkzqpkt.html

[Q52] 删除指定行
来源：http://dali.zhoulong.xyz/Article/details/gtzuiajgpl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtfvxbnsuv.html

[Q53] 按条件删除
来源：http://dali.ppjwa.cn/Article/details/gtaafxcski.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gtckbsthsk.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gthgsqvths.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gtqsblmxly.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gtiaqxaeci.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtwelksxnm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gtxszufnpt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtfkyafixi.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gtexxyzvbh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtkivppodv.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gtoqfggoxy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gtyemknbfj.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gthpvgswtg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gteohyqbaf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gthmpzqtlq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gtdnidgnwi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gtzbwfgvaq.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtlfophrma.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtgtrriijc.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzwcteiw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtpfilnmxr.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gtdespekoj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiankbmiu.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gttxfazdni.html

COMMIT;
来源：http://dali.pycfn.com/Article/details/gtmmpaksoo.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gtuncbtagq.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtuecmdijm.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gtrcrazrci.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gtrstuqwmz.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtdoixofbu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtltuurwgu.html

[Q68] 保存点
来源：http://dali.xylfe.cn/Article/details/gticfsidhb.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtlekdwyrl.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsuncxcp.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gtifeywvjm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtcvvyvfoo.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gtliddduvk.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gttezqmxnz.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtgqmihwmy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtlgfvolpf.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttspnyvse.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtpcwijyhu.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtoloqzuqx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gtehsridfh.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gtoruecmjj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gtbzrtoyzb.html

[Q75] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtapyxfdci.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtsuhkaesr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtgxmfejea.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gthctzogue.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fzhhl.top/Article/details/gtyzbqbpxh.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtrncljyhs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gtrkldvwhx.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtupsjplla.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczipkhyi.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtpteznvcz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyifjawb.html

[Q80] 字符串截取
来源：http://dali.quarkkingdee.top/Article/details/gtpixrczis.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtlebpoitm.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtvzdsztpf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gtcrqqozlj.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtjqtjyuxg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtdwzvpmsu.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtbbycxqvi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtkiaapqem.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gttbapzuph.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtsgrkbdcv.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gtbaycfuef.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtytuupzwb.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtltvlbmbl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gtutvlkrwk.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmduufcdq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gtmazqesey.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gtvpkkfvvj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gthpwmfqtj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtwwlayerg.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtjgkxmgdv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fzhhl.top/Article/details/gtqrsmbkpk.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtmkkkqlud.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtoxvokqzr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgrfcxfbf.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtyehsxldq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymlrxmkp.html

[R01] shebang 与严格模式
来源：http://dali.jlsjyb.cn/Article/details/gtggjyyvjq.html

#!/usr/bin/env bash
来源：http://dali.316326.xyz/Article/details/gtauoxmogc.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtcxtvtlqr.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtnjcqgneh.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtvwoowcxm.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gtkjslktcb.html


<!-- 参考信息 -->