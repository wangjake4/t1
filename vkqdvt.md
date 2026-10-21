代发 wailian999

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtagzzbmkg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.haohaochexian.top/Article/details/gtpwqbvevc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtzomdgyrp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtalwqegjy.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtjznfryjq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtigfomorv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtratdrciz.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gtdzdqwukr.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gtgcxykape.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpdugkkje.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtijpglrkl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtsnxabzjm.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtlfuaznvr.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtgmxrwkyh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gteoyxwhhg.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtzmunksaa.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtemjqyopc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gtxezrnpha.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtnhcxkmrj.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gtqruanaqz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gttpofyyrm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.smart0.xyz/Article/details/gtrsfbrbku.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gtjascohzt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyzeyllb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtrhavebea.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gtaoplimpa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtgvsckuqw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtssbgepvp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpaihknwe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gtxrigfmrm.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gtvwgmgefn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtwvdmixmi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gtpswbxixb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtysrzwhli.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtzecbhcct.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gtnsbaqrdw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtkssejudm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gtvqnjgzlf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtguodhcxe.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gtmpcagzzf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtrbjvxwlw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtjmqjfqcz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtnycbejfb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtwdorpfit.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gthukhbywv.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gtwfovnyrh.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gtqnkfvjol.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtlugntqzg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gtovgqoeig.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gtxvwoqezb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gtmvyqidhb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtcvveqsrn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtivydlbbb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gttpbcpmyf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gtujomiais.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gtsnzghkdv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gtugonhzwg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gtcuidypdd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gtywjjrkss.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtqpcsazub.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhixingplan.top/Article/details/gtghmyiwjx.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gtuxjzazis.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtshwueeqk.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gtoymtltfw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtslamwisr.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gtubdfqdwe.html

[P07] 防抖与节流
来源：http://dali.jiagoushi.top/Article/details/gtbrojdikp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gtbrebhhfk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtjyqunohc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtihulsnvg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gttdtnqbgs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xziqi.cn/Article/details/gtwzrppern.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtxhhafxzm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gtafkkmyyk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gtyxnhsviv.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gtqdydhtpo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gtweswgvfz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtdtdofhnj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtwqibknxz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtwrawdeto.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gtabmwiujz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtvtftibmz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsutvklka.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hongshengwenyu.top/Article/details/gtnozyfypo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjlbybajs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gtezlhsqjx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnoevtzhn.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gtqinfhzir.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtcbapzwvz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gttpdurtwq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcskzpxxg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gtxsgmmmhx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.andypj.xyz/Article/details/gtekeqyuuh.html

);
来源：http://dali.ybcxt.top/Article/details/gtnjciljoj.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gtlcufwcwx.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqhxarkg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtijgteipx.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtriuyrvte.html

amount DECIMAL(10, 2),
来源：http://dali.jqgufenzy.top/Article/details/gtxyoidkqr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sxryk.cn/Article/details/gtnuatihbk.html

);
来源：http://dali.meibo888.top/Article/details/gtclrpmguy.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gtvfcstyss.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtechoouwk.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gtoeedfnja.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtancewnva.html

[Q05] 重命名列
来源：http://dali.nanxinkj.top/Article/details/gtzweroojx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yangfankeji.com/Article/details/gtowilekjy.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gtrsupwbnk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gtoscghfpq.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gtkkwkoyim.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gtiqrtotpc.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gtrlkvitqw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtwhldtfsd.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gtvxtpepul.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtnoqmwbic.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gtfvwteccd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtptckjbux.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtdaqsczbi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtjwzvqplk.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtrjzcacti.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdiwrnvin.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtkxadnfmu.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gtlgqcjadu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtyvglegjp.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtbedszgvl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gtixhqhdgn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutvkfsqa.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gtiomlxqex.html

SELECT * FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtybeiwmpy.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gtnsxbrvjt.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gthrcbiqlj.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gtsqvuazfk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gtxmzqoqgd.html

[Q18] 模糊匹配
来源：http://dali.bjfxy.top/Article/details/gtyrukksfl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtnmiyhhdw.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gtanjlqqkf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gthnedytey.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjcfeyre.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gtdhwptfdo.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gtslnsgxak.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtbhivorbp.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gttjcwvmsg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gtlhlkygfr.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtwurusdvf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtetrkrgsh.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtnvankgtm.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gtnijhkkws.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtrtglnzrl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtfggbtxgo.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtavfmxpbf.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gthrydnvdo.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtzsrwuare.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gthudhyqge.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gtfaqvqwuo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtwquiltvm.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gtkfbavzyv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gtswzmbakc.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gtrnmelqiz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtnzoszyyp.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtcvbkdykq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gtndrmrxpw.html

[Q32] 分组拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtazcauonn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtbzgihffn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtrdkqbwrm.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gtjbmxxybn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtpruottax.html

[Q34] 每组取第一条
来源：http://dali.shuidangran.top/Article/details/gtbwouhaow.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtxummdhiw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gtmumjhsft.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gtjwawxwdj.html

[Q35] 内连接
来源：http://dali.guowangkeji.top/Article/details/gtwzdbzmda.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtblziplfl.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gtftqnvzcd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtkwixmgmu.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gtkjottugo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtejyekiak.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtqrswwfuu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtzwfwvajt.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gtoptnsfhg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gthpyollhi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtccwbwkic.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gteozlchha.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gtkntjbmci.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgucpwjx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gtkkruujjo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hfpthk.cn/Article/details/gtdmiiixvc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gtldwsvnge.html

[Q42] 连接条件附加过滤
来源：http://dali.guowangkeji.top/Article/details/gtsoxcqfih.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gtyebopykj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtftupvbjs.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gttqcvzvtr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gtzehebkqb.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjrawzsv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gtjhygbqhn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gtacfyppug.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtthjtdema.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtpporxchi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtjassicjx.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtxcndflxb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtfjhbtuha.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gtrkwwpdfk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gtxifcsepe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gtnjngihhh.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gtygljvxro.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtculeeibo.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtvmbvxgtt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtspocfuhj.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gtwpizbahr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gttmgdvkuo.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gtjepmwbiw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtzgcvndrz.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gtdnfdookj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtinvubvbi.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gttusjxhwu.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gtojuvnbkg.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gtoxcxvcab.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtsegomiij.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ehwqpu.com/Article/details/gtemofockd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtyqbbltlt.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gtcwtwwzmb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtdjbakjab.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gtkdcxqbqi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gttwdtuaaq.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gthfyqhkhs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtfkfnvfgp.html

[Q60] 取上一行 / 下一行
来源：http://dali.pycfn.com/Article/details/gtspovuzdr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtrwqjyvgg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtncvcnyxx.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gtdpnbueqb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtugraftla.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gtaewfuqyq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtvlmesvap.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkthzjfr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jyoumei.cn/Article/details/gtcmlcplvo.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtzltcmiur.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gtisobzcfg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gtnzgfrwhi.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gtkjkntxvt.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gtlitnuezs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtwydpufeo.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtkwygphzy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gtzdhhrdll.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtlrxziolu.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gtxmvgqjfg.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gtzfepdxda.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtfuupltqd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gtnslgwxrc.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtsbchsiae.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gtpkxthwgm.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gtjalpegio.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gtnetgpnli.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gtwrbmkpen.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtazdzpiem.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrvqhnlh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gtsuzqahpi.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gtkvswmufh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gtpsfnlqyi.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtwrlbiaih.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtzphubzar.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gtybstrifx.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtoehsvyso.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gtwbmoqogs.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gtbbrxljjj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gtbdeucikz.html

[Q78] 当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtmojxagom.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gtetrtwfmo.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtaykstamz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gtvjtaqunw.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gtoqsisqbq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtxpdnejwd.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtujuxjnhn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gtsavvhgqa.html

[Q82] 字符长度与字节长度
来源：http://dali.guannengcc.top/Article/details/gtgqferjux.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtydkfhadu.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtnfvugpsz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gthgqtpcjw.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoryzatvo.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtrwkhiltp.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtpwbehpyd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gtwlddhint.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gtgegwwilp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoknomtr.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gtoxxwnhns.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shangyingyoupin.top/Article/details/gtzdkpmpob.html

[Q88] 行转列（条件聚合）
来源：http://dali.meibo888.top/Article/details/gtfpxfylpg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gtnbxsnfyh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gtggyuyjfs.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtmgqchyik.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtvrlnoiwt.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gthfedrmnt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtdsaxlcxn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtshwurozi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gtskrekzjg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttcdjjqqk.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtgdxeatko.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtvjbjvvpc.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtptqyftcu.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoobghua.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtjesxwael.html

[R03] 只读变量
来源：http://dali.shuidangran.top/Article/details/gtbwyywsqv.html


<!-- 参考信息 -->