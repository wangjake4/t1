代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gtyhpmdlfd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvvhefbc.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gtixydwnce.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtsnoodqjq.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtcbkbneut.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtmwxtxrjq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziyfimau.html

JS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtgzakkuzb.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtwoyamjom.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtsetyriqu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtjvzonynb.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gthxqcapmh.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gtipiadpzd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlessnggl.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocfuqolx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvhlaqjhh.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtcghzqivn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gttqtlvgou.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gtquiypnpl.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtyzryvnra.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtqrrtyhab.html

Java: UUID.randomUUID().toString()
来源：http://dali.daxiang520.top/Article/details/gtehlcilca.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258888.top/Article/details/gtvbkqnwuc.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtuzailmga.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtpmggru.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtzooyjqlc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gtlcwjwxdy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtllhfycob.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tianlin.xyz/Article/details/gtoxpwynki.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258888.top/Article/details/gtokgjomta.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtgsvcgdpw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ehwqpu.com/Article/details/gtqiefpvwr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gteoraaodf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cashguo.top/Article/details/gtkjobrnoq.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtvcowdjpt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gtynsmedyw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gtjazeptyk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtstzcaula.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtbqlufkjm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtlfoesspi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gtrhconmkl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gtvojqilwu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gtqoomahah.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gtukrngpui.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gtytfrhnpo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtergxvnsa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtwwunlxna.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtwfhsuagk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlssjvcyu.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtirqoeciy.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gthatrsybu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgliltiwu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gttezewcdw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gtskgefjqp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gtqdmpwewl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gtthwuhocv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtjfphphvl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gtlkvuokkf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtzivbanxj.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjczousis.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gtbotaybqv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gtlbryomkc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtjcxcaani.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gttbyitgvd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtcfsxykjl.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gteeycolbp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtdferwjbs.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtmhlfuuad.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gtijgvioed.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gtyvdygque.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gtxcnwvitn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtczcwvj.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtvyaafgwu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtkemqsvgm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtphjdvwmr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslhesksl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtcwlrdsht.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gtszcbukfb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gtbfnqpwcc.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gtkdojlbgt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.0kj1m.cn/Article/details/gtesdobdcr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtsjloqgpi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gtnddmjrol.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtdfhynxam.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gtuvaeeokr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtyrfhakza.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtytxmjhhv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gtyflxifyw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdzpdiztd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gtgwfqsbvr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gteflapdmn.html

[Q01] 创建表
来源：http://dali.jqgufenzy.top/Article/details/gtelebdtns.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gtozlekkpq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtgqqvtjdj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtqqkxxqxc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gtynqvgsuc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gtfkjfgubw.html

);
来源：http://dali.nanxuanxn.top/Article/details/gthkzszsdy.html

[Q02] 创建带外键的表
来源：http://dali.nwbrower.top/Article/details/gtyhatxphc.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gttaihmpim.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gttxiggtjq.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gternnppic.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gtslvzhymu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gtszyjcuxw.html

);
来源：http://dali.yonumen.top/Article/details/gthsyyvymx.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtqojgfxhf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ppjwa.cn/Article/details/gtaxnupvac.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gtcvpfspyq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtdmxsoghx.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gtamanztmy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gtsoufehdi.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gtexqgnjuy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtdzyuyjgv.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtieqfykhf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gteovjrbla.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gtfhgjpqgh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdeualxa.html

[Q09] 创建唯一索引
来源：http://dali.shuidangran.top/Article/details/gtnigfimft.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtlsnnqsum.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gttvcbeitc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwetecwhx.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gtowoicfne.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtvwfipivy.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gtrsznlezi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtwekqzmtt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gtuyxqshzn.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gtzvmyxfju.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtfxqhyofd.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gtzjzfxrxs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgufenzy.top/Article/details/gtzsdyzxvc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gtjqxwltjx.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gtyymvhkrr.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtjqrkvdoy.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimakuxpp.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gtojhvrsvi.html

[Q17] 条件查询
来源：http://dali.jinqigufen.top/Article/details/gtawahqusz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxinkj.top/Article/details/gtgsoueqkq.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gtpntcsmnh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gtekrutpmt.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gtzhnruutk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtwycjkjkh.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gtyqdcgklw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gtazqgmpbj.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gtkvepvdju.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtdhvhfewj.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gtjhieofzn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenjidiqi.icu/Article/details/gtyqsntxqo.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtbdwgtxcu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guowangkeji.top/Article/details/gtkebpakil.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gtsoggigev.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtpsdxbwyq.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gtuawigpzs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gtzioktkkp.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gtwoqcypcl.html

SELECT COUNT(*) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtsutdvgdw.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gttuzuuhgo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtmaefrtjp.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gttrmrrkgk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtxwvvdoui.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtzfocsofo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtrsmougne.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gtgmyrivuk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtcvgwbmbu.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtlzztswgo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gtkvhcvaut.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtkdmzdpia.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtmwruybvr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gtxyslqxsh.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gtspowzxwp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqwaklkm.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gtoshwacut.html

SELECT * FROM (
来源：http://dali.jqgufenzy.top/Article/details/gtvgavxotw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gtndfdkzcs.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gtrxeuzvvv.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gteqfrelyj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtximlkjrb.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gttgtqkznf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtmaeatiua.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gtfjdapnjz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtgxrtgnci.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtjnkyxxxo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenzaomai.com/Article/details/gtejmjuuol.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gtdxxrwpdh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gttnavrnqr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gtbppibhew.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258.top/Article/details/gtaawqahls.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gtqverioce.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtdiwjerjf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gthjazqsjh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenlongwang.top/Article/details/gtqnlfwahh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gtpbywlhtb.html

[Q42] 连接条件附加过滤
来源：http://dali.xziqi.cn/Article/details/gtmojpdgfp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gtaagzlomg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cashguo.top/Article/details/gtuugbiluk.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtizdknxwd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gaohongyu789.top/Article/details/gtpfagxykt.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtmgwpuwsa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gtllktzefp.html

[Q45] EXISTS 判断存在
来源：http://dali.yongpay.top/Article/details/gtpltuupkp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatphdnro.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gaohongyu789.top/Article/details/gtloqowtfn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtsqbqierx.html

[Q47] 与平均值比较
来源：http://dali.nwbrower.top/Article/details/gtlnloblwr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtcglvocyj.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gtaernpclc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gtlkncezon.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gtpqwrpsvc.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbraicuxq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtoycrjbcd.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtqqehieze.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gthffvlzfl.html

[Q51] 用子查询更新
来源：http://dali.jiagoushi.top/Article/details/gtaqqvzfov.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtibrxbnnw.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gtypfnrceh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwjyrfsl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gtazuwyssi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtapbmzimm.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtxycenraz.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gtayizpjxp.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gtdxijsgmv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtpdemojau.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daria6918.cn/Article/details/gtxmqfrxmg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtjztsboqe.html

[Q57] 行号
来源：http://dali.hysaishi.cn/Article/details/gtmlvdkxio.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhcqqsjx.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gtsdxwfrex.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtgvxhhtks.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gtjjgqllol.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtfcapuaab.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gteqehkhch.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtzoixbhrb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtbnhazvsr.html

[Q61] 移动平均
来源：http://dali.hammf.cn/Article/details/gtimuvtseg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtcqovmwzs.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtrrhazi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtchvdxlux.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtrawxuuug.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gtiasfknsc.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtnhydwxzf.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gteqethyuc.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gtniwwdgts.html

ROLLBACK;
来源：http://dali.316326.xyz/Article/details/gtirlevyho.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gtqdygfukm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gtkubnxxjc.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtpetsabjg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gthlxpnlni.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gtptkargak.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtuqkxbrro.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gtqqlyefka.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtwbfiltll.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtmwfirrdp.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtzfulbtga.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gtqgbtwcui.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtgtodraos.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gtqttdpxia.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gtcvpzcxvt.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtsyrvovkp.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtfqpphuny.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gthtwyfyuv.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gtdrppjqwc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gtyfrsfvjt.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gthkcfexgg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gteqyewqxe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gttchzdxnl.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtwuxznswc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gtiqetvjfw.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gtqjymiavy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtqnjllrpc.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gtdpbacotb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gtbdymsxqb.html

[Q79] 字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtypsxvini.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtghzesohw.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtsrqdornc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gttcxgnsmv.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnupghbe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtpjujimla.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtjfdmbakm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtvbqcvulz.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtyesppztc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtqeauvhph.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gtiekdazzr.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtlkwcpmcb.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gtjfcewzoq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hysaishi.cn/Article/details/gthbwxpzpx.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gthyhlqhev.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yonumen.top/Article/details/gtvyvzvbfr.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtzqrfjtmt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtbgecyofz.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gtlkjgjfvk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gtkjnuxpmz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtgenqfghr.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gtyrtdxgcs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gtjtvoplot.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gtccothfeb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gtfjvtojrg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfbmscuzi.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gthncmmayz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvjrxwycx.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtzuagdokd.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gteqruucfl.html


<!-- 参考信息 -->