代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gt2vezyehug.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gt2rucxkmty.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gt2kjxyqjfm.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gt2tgwbxbos.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gt2hoqejnyb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjxszwqe.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gt2tjqqjspb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ttsrcjrb.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gt2drlmdafz.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gt2nitfiwia.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gt2igvygozx.html

JS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gt2ukyqdtjz.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2yboygjcc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gt2ygsqbesz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gt2zfubqzhp.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gt2tyqbcntc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gt2vuzrzcqn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gt2muubvvre.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gt2fapqlvzb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gt2pyyfecel.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gt2wiabaddc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258888.top/Article/details/gt2sntucslr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2flkycjkf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gt2vtaykaxp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gt2kjgpyjun.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gt2clkjcooy.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gt2ygapsuoa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gt2svtaxtxa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gt2mguibora.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvcfyqsh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gt2sxhokgeb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uyeuvkil.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gt2wclkalay.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yvedp.cn/Article/details/gt2vhohqdxq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.redwolf501.top/Article/details/gt2lwgjnbcw.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gt2dzzqqakj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gt2wluuqkob.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2fvpgjgyf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2xoseyzfx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gt2inwyilwa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2kmvfwxde.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvagmvxo.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gt2qvqjtorg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gt2hlavrrsp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gt2onzfdpwr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gt2zikghgvg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gt2pwvqfhuw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxuanxn.top/Article/details/gt2lrbrmgnu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2ffeqswqa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gt2fgspfqwv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2droyfkcg.html

Ruby: a == b
来源：http://dali.jinqigufen.top/Article/details/gt2vggocevd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gt2tufnmdfj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdjljheh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gt2jqxypefr.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gt2fztuscuz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gt2thdwdbrc.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gt2nsrtltfr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2mzrgzeae.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gt2xvyttzjk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gt2wrdbhxwp.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gt2osntdvkb.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnrondps.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfgiekuz.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gt2skkkyqxo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gt2jgeerrkf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2qahgapde.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2bshgdqeg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gt2qyixwgqe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uaajjqiu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhengqikj.top/Article/details/gt2hfpivdtb.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gt2fmlqtbed.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gt2urivdlyt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2rgdwcqen.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gt2cjivoklb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gt2ucunbddf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gt2luhrfeus.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenjidiqi.icu/Article/details/gt2uavhswvv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gt2sroapchr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gt2kblblbgb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2aetgzcae.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gt2zxwowraq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2jeyojsjk.html

[Q01] 创建表
来源：http://dali.tanke756.top/Article/details/gt2ufswdeeb.html

CREATE TABLE users (
来源：http://dali.jinqigufen.top/Article/details/gt2ohviemzl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsvlwlfe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2dwdhcreo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfuzmmsh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fengsongda.top/Article/details/gt2oomowxol.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2khikyvdd.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gt2fkcolmaq.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gt2mcreqyza.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2khlvdowy.html

user_id INT NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gt2zeflzqks.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxkhywdx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gt2hqcxvnae.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dntksjfp.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gt2nviteypf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gt2vwtzzzko.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gt2wwkerqny.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gt2fsewregl.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gt2wlazntdp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zybzlxgx.html

[Q06] 删除列
来源：http://dali.hnqzz.top/Article/details/gt2mzhbywkr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gt2qgtiwjqf.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gt2eazxhwsu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gt2iawqblzy.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gt2ikgsbqpr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gt2ollfshys.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gt2fpmhkols.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gt2bsdxhusa.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gt2xvghgovy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggvgkkfy.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gt2tkrchvcl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2berluxrg.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrzlahwi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gt2prjpaxou.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gt2qphkwrxm.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gt2wxquhsbx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gt2vsubmbgf.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gt2qqpuorei.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gt2dbioayhe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gt2wkvukzjf.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gt2qtytemmb.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2nuydduum.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gt2gawyfeyj.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okpnbvxm.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gt2fmvjffqk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkqjpdx.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2vzpqnnsd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gt2opckzceu.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gt2lvfrgdqg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gt2imnqdlne.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gt2ljjztcks.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gt2erdmtfns.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gt2luhdotfi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gt2zbzfbiur.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gt2qveiujvf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gt2zsoeedbu.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gt2iqnddzth.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gt2hinbireh.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2mhofzgaw.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2butmeifm.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gt2vkyvaqif.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gt2yqtcakrg.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbjldehw.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2ytuwbezi.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gt2znhrnelf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2wimvbqgr.html

[Q28] 求和与平均
来源：http://dali.yvedp.cn/Article/details/gt2pogqbdwa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2wsniompp.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2aoarhrsy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2lxuqktvj.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gt2pbucvdpx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxllsdnv.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gt2pwrlewax.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gt2dyttpvhf.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2taizvcda.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2iyceakez.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gt2htcmoexr.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gt2kcoappyc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gt2glcjizrr.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gt2hlevegqk.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gt2srrkgghd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gt2giwzopwx.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2viggstez.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gt2tfdyilsb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zektovyo.html

[Q36] 左连接
来源：http://dali.tian-w.cn/Article/details/gt2fhnokjwe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgwxfgad.html

[Q37] 右连接
来源：http://dali.yj20258888.top/Article/details/gt2zjumeivf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sweek.top/Article/details/gt2tsoffvvl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2arbwzskv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gt2ovtfgqie.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gt2wglqredw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gt2umsxuzav.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gt2fjhuslfc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gt2ljnukgkt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gt2lkefwpmu.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gt2gtgduytd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gt2xcmsnkcz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gt2adzvhgvk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2salzejoa.html

[Q42] 连接条件附加过滤
来源：http://dali.dianchejie.cn/Article/details/gt2jycjlxsy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gt2ayryqblc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gt2vglwcprj.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gt2gbkmnomb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gt2qybgzyit.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gt2iphnufrd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gt2fuvumuzy.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gt2yypxulup.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2wzdblbep.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gt2xjuzjfah.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtnlihwh.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htyndpcg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gt2gknqfbrj.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gt2ikmsrmui.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gt2bezhpsrx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gt2plwfbssf.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfjjztmt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2vcxcfwer.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfltwfxu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtdenzct.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gt2wefflibe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2cxcjxijx.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfvyfelq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2bdqrnegm.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gt2rqckssry.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ehwqpu.com/Article/details/gt2gztmoraj.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gt2qijnpmhx.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gt2jlbzbjlo.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gt2dckvzaor.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gt2emfvudrt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gt2mezwiowc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2qtlziqey.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gt2qmbacoyn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2vaumwtdm.html

[Q58] 累计求和
来源：http://dali.meibo888.top/Article/details/gt2uhcelegc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2dmplsagf.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gt2kehlbteg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2oreujfoc.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gt2yxiumvbx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gt2vpsbycrv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2nkjrgizb.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gt2xjahenus.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2hdsibwvd.html

[Q62] 分组占比
来源：http://dali.yuxming.cn/Article/details/gt2iyxgyacl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfolujov.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2umzqhxhb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gt2nklepnra.html

[Q64] 提交事务
来源：http://dali.wangdashe.top/Article/details/gt2vjfwgscv.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqlpbbkx.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gt2vmdqaprv.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gt2aosqgwwh.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gt2ucrwfjpk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangdashe.top/Article/details/gt2hqxkuwyg.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gt2tmlkynrg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gt2jjvfwwgz.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gt2fraqdjbz.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gt2bxnadlhz.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gt2qkbndkhk.html

[Q69] 查看执行计划
来源：http://dali.jqgfzy.top/Article/details/gt2nksgnqbb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gt2koycrjkx.html

[Q70] 更新统计信息
来源：http://dali.chenjidiqi.icu/Article/details/gt2rcnmdsme.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gt2rghnhiba.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcchyjvx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uiyoping.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gt2cupxhvxz.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2fpqwtgmv.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gt2wccoooaz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gt2ovbcqsga.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gt2iqodqkkd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gt2dyyeulls.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2fnemdpti.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bncagdqo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gt2kdrxxkza.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gt2ylfgkpkp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gt2tvvmhdwe.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gt2qldufsph.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gt2mrhvvmwb.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhbhjwuu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gaohongyu789.top/Article/details/gt2ztsmvkuw.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2qneddokg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gt2joentwgl.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcafohmw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2svquyahx.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awmtwjbt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2muyswedg.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gt2jgdjkegw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zelzrors.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2smhmiivu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2qiuvwbhk.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gt2tfzwwkct.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2heqgmxrv.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gt2amschmni.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gt2lhztjcyg.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gt2szpmjmyv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gt2ggsfpuca.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gt2yerzljpe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gt2knmvqbvd.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gt2ovebeoss.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gt2izjfjdyc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2cdqhlbei.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2gjnocthp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2jqlinqrg.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gt2yrjtqlmo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258888.top/Article/details/gt2buapopkt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbsjjaco.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gt2hvglnbqi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2vcbsfkby.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gt2rlyikmst.html

#!/usr/bin/env bash
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctcvcbbf.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gt2blbanysu.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gt2fviqneke.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qutplbfh.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gt2cvybsjpf.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gt2vqvwdmul.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxduzby.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gt2kgraoutp.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gt2fxhmpplw.html


<!-- 参考信息 -->