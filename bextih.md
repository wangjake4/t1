代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgfzy.top/Article/details/gtoslehoiw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtkgeztayh.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gtkndxigab.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtsnzgijnx.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gtsmluaxlt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhiwuduotai.top/Article/details/gtvirfsluz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gtvfsrwqar.html

JS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtznuegezv.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtceufejsk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtoqexfjah.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbymyxoh.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gttfbukcrn.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gteuawwgre.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcdapyimg.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gtacrcoerd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynmmcxmi.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtgotlfqdc.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gtdsiizcjs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gtqwuzmyfp.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaryydeg.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtulsipzcb.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gtwsnwmlim.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyttixlt.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarofjniu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtyduzspcl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gtdqqtlnnu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsomhfqfx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiholkye.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtmnfmzrlc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258888.top/Article/details/gtxjtnstwc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtyekwprqb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ehwqpu.com/Article/details/gtlmqxvock.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gtmfkblpcr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtfmgdmctm.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtyyjmkorw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gttpqhozhi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gterktlsxb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtiqvcjmmp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtdwvmpjiv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtnuyodmdj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cdnleiting.top/Article/details/gtifrtwwor.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gtyvkeqmji.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gtxlknchxd.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtvffvfcyo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gtgadawuno.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtnqdjrpvf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtkcspgsro.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtmkkzllot.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtmbxopfys.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gtykkcwckh.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gtrawkipcz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gtkfnmmcxj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gtppniphgv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtqzfzczeo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtogmdciwe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gtceqkwtoz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtamnysuih.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcyvlqaq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtfyasrviq.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtjphgrclm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gtkxakvbif.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gtaezjfban.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gtbjnvnqyo.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtgfejnaur.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtmqbeqtvo.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gttirvqmuh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtickqxckd.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gtfdrvnxsx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtyjhwkpyz.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtakctlrmz.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrcvdmkp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dashuyun.cn/Article/details/gtazvhbnel.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqdpfpxu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavgozdkp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtsghkaocc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtewfcokkl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsfltoqm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtsupkbtpv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gtkxupipfu.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gtakoedhal.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gtueotageb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtobnvxytk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gtmnacgrym.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtxdunnqjm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuxming.cn/Article/details/gtygkvbwif.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jlsjyb.cn/Article/details/gtylszbydn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gtqrnnavmn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtcmbfbenl.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzocopqpn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqdfngcy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxoypnmnb.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gtdydbigko.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gthfmevldh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtbgfwywis.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtaxmmrjuh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtpzhksbcs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gthavlcdqm.html

);
来源：http://dali.gotoacloud.top/Article/details/gttawfjkdc.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gttbdsyqpz.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gtyzvpkrhx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtvqilxbev.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtdahtouoj.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtadfzsfsi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gzhubu.top/Article/details/gtgkbkmcba.html

);
来源：http://dali.dianchejie.cn/Article/details/gtzcxlhjdg.html

[Q03] 增加列
来源：http://dali.svipenyu.cn/Article/details/gtzlmzcbgx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtcjewrsvq.html

[Q04] 修改列类型
来源：http://dali.hnxiangtu.top/Article/details/gtodjyvklb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwulayxvx.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkfyiroo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gtqquqkgpj.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtdydrweuc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gtrqhjkfdg.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gtgsnftbjn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gtfxjeelxc.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtkagicwar.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gtaodzvawv.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gtcrvtolgj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtklsickwp.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gtjzgclfbm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtyrhbdlhu.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gtywbpnpqs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtvsfmahdx.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gteotibsfa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cheryme.top/Article/details/gtahkyxjvv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gtptcfcxta.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtqyqkfmpf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtrdgwweev.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtphlkpewp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtmupwrmsk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gtzosbxwwx.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gtqlzgtanz.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gtzxohfahz.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtwjzprmug.html

SELECT id, name FROM users;
来源：http://dali.birdmap.top/Article/details/gttfjhttvd.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gtttmdalhj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtxgwerjoc.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gtrnhgimih.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cashguo.top/Article/details/gtcmdpkljk.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gtecoofgwt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gtxlmrranu.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gtiyhmlmab.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gtsvwfomwl.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtquuuyehi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtmcjbxzne.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gtjgndioza.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gtpsyjbpcy.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gtrrmtgtku.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtkpouffdr.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gtucsvhxjn.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtzibeabid.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbpgzdoy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtrnnoraqg.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gtrbkncfbe.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gtjviiakbb.html

[Q27] 条件计数
来源：http://dali.jinqigufen.top/Article/details/gtluktqgmd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtqakgxlpk.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gtgevathsq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtefvabjcc.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtkgwfnvew.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpklnide.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gtpukwrsfx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtcvdfhjqk.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtpbwlfvtj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gttyenxirc.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gtihrisicv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizdukhjd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gtdaoidcts.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gtzrpqrbwd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtcioxtdqo.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtewzovxdg.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtoazwcasb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtgapqober.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghclipog.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtihurjfai.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtwihifsqe.html

[Q36] 左连接
来源：http://dali.tian-w.cn/Article/details/gtuhlnovhk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtjfhgmyyr.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtnlgsdidz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtlgetrvhf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gtidhbwsou.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gthhwuvefi.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gtfxwsontb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtvrmgmjrd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtwngvobpw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gthuknviqg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jlsjyb.cn/Article/details/gtqbbyvmbt.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtfnbzlbok.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtmirfmdnu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nwbrower.top/Article/details/gtxvdfcoen.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gtaorracsa.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gtfpiyhsxc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gtmrrpcylo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtewpvndik.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gtwovoiznr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gtnbrsbgdv.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtvygpbjiv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gthadkjdif.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gtbpngnugo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtyvlmlvvh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gteorlxiep.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtyutwwvso.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtqwhyqrib.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtsqtaathb.html

[Q48] CTE 公用表表达式
来源：http://dali.iojbl.cn/Article/details/gtobfrtwjx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gtqhvbllne.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gtjdimlvzl.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gthbisphgf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gtwhkqamjk.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtflsbfnql.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtitjhfryt.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gtifmvcmax.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgpepjgu.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtfgeqnwsi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtjmkovshy.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gtyguvzzzn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtcytkwhkz.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gtnqssjzny.html

TRUNCATE TABLE logs;
来源：http://dali.chenjidiqi.icu/Article/details/gtauqoerlc.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlirppbjp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtkxqrdcpu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtckkkngdq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtdkprohpb.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gtlnzskgby.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtherguora.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtgstprhat.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtsdwvflok.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gtibibilis.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtsldenhux.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gteadpvlmy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gtjiobjjrj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnnluisf.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gtactsutly.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtqutinzfn.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gtvivihnau.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtrzosbbvi.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gtgrpltynp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtmqfcmylq.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtlaymqohl.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtkrpfqzer.html

[Q65] 回滚事务
来源：http://dali.pengpengdd.cyou/Article/details/gtaoscbfbr.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gtxjyylfad.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gthjmaotwf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtfqofxler.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gtenjfrklt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtwdchzfta.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdugbsjpm.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gtultnobvh.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtbxoykxug.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gtkxpzeanw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbniigbwv.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gtcilnxjhp.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gtxxjgwxff.html

[Q71] 查看建表语句
来源：http://dali.aibaodan.cn/Article/details/gtoyvjgbnt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtbjscvdkr.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gtqurvbljv.html

SHOW INDEX FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtzmkiwgic.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gtbacsjrmh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.svipenyu.cn/Article/details/gtuqnkngfq.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtaowgmizb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gtwzhopuhn.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gttzhyluez.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtmmhewose.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtdrcklnfp.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gtinywigoa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sysykeji.top/Article/details/gtihzjboyy.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gtivockejy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gtvvhokwph.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gthbgmkspj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gtnxuxibfb.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtskvpekov.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gtmhgyutul.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtwiissyfq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtpowqsrdt.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdntuyukv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gtnnhvlbvu.html

[Q82] 字符长度与字节长度
来源：http://dali.pycfn.com/Article/details/gtmtdavinw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwlgsxix.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtpxgbqzhw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gturfviobc.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtasjinhwn.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtyarvhyid.html

[Q85] 数值取整
来源：http://dali.xylfe.cn/Article/details/gtwczntagb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tian-w.cn/Article/details/gtdzqtryng.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtervafryy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gtxqekeuoz.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gtbabetwcp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtemblrfvg.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenlongwang.top/Article/details/gtmdsoeces.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqqqzphx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtagcbkibc.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gtsfegzlxk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtjjlgkbol.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtfizkaxrj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gtgdxpgoyd.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrhcutyvl.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtsbttcumm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtprxmawqm.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gthcrrliem.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtjowgwxbs.html


<!-- 参考信息 -->