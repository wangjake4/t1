代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gttrkoaerh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtkqvaggfh.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gtttjfrniv.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gtaxmdaunp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.havefunace.top/Article/details/gtpcxjunxe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtspnxiwlw.html

JS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gteevjkfct.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtsdokhzfi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gtyzxbudel.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gtfgvyffcx.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtyuijoiwy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtawntdjrh.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gtetapxlrh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gtutbfqfyi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gtehjvzico.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzterzzrw.html

TS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtlyvcouph.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtlowwptpf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gtyykwymxt.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtilooheao.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gthbxsixnr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnaawguuz.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gtywiqefru.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfaegaklu.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtajnphbro.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gtfylsipfq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtksmdzfyb.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gthcvekils.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtoyeoizoi.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gtxnxcaweo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gtfdvmratu.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gtrjyooyup.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gtnqnmzndf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyjtzjdm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jlsjyb.cn/Article/details/gtuerdgdak.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gtpbhfqmkv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gtiaqwhtkh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gtjzltjryp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtyzciqytr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gttowtvcmu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gtpdzowkbc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqihxdph.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gtxqsshrnd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gttfyeomtq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtzxbfacuh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtewjbanvk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtzkjettal.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gtmryisxgx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gtmsauvvlu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gtiexmhxno.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.svipenyu.cn/Article/details/gtgamuybhs.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gtisfzubwq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtupclrcvu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtjbaeqbqw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtjtmobvym.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtjsvasazn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtdvohepfl.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylvsbfrv.html

Ruby: x.length;  x.size
来源：http://dali.c1oappe.top/Article/details/gtzmkwitwh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gtdosjexso.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gthzxszfwc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhiwuduotai.top/Article/details/gtuxwqzhye.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gtcnduzdfp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gtbewsagwt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtlnqysatm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gtsgbbmwwy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gtjlrsljft.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtnautsvff.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gthyeklmzt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gtrszdmaxd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtuutpfjuk.html

PHP:  if (empty($x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtiivylhqz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtceiqngls.html

TS:   if (x == null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtsooakbuc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtfmxlaboz.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gtuyjcdzjj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gterkzlxpl.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybcewuxb.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtczabmtdz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gtvnuwsckq.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtqfptacsi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtuzmfcsrt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtgurpliqh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlzrdwwx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gtkecxthin.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtsossjdnk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gthzpnjtri.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gtjhxlmbrg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gtpfpitdfk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnioxgbod.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gtjqfcojfe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtwjkyqmzz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaiqjvjdw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gtswgzjist.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gtucrzovww.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gtdmjxegux.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzmuuixfd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gtvzjywfcd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtsqdqdahl.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gtpqvenndf.html

CREATE TABLE users (
来源：http://dali.jinqigufen.top/Article/details/gthxdzrbxv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtvzdygmix.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gttbktkqcd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gtfhbjlgaf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nwbrower.top/Article/details/gtwbmxnaon.html

);
来源：http://dali.smart0.xyz/Article/details/gtfqdicuro.html

[Q02] 创建带外键的表
来源：http://dali.shzxlz.cn/Article/details/gtflifiycx.html

CREATE TABLE orders (
来源：http://dali.xuetiantiany.cn/Article/details/gtmsqhrzsd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtjivskgwn.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtmqzbsquv.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gtooxzwsta.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyvdimka.html

);
来源：http://dali.316326.xyz/Article/details/gtwqskzwbj.html

[Q03] 增加列
来源：http://dali.feifeiyinyue.top/Article/details/gtvbzivlak.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtkvjlbdnb.html

[Q04] 修改列类型
来源：http://dali.cqqwz.cn/Article/details/gtathxnrpa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gtfezhvjdr.html

[Q05] 重命名列
来源：http://dali.cheryme.top/Article/details/gtemdgehio.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtoenotwpw.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gtegjowbka.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gtzilrkzkz.html

[Q07] 删除表
来源：http://dali.hfpthk.cn/Article/details/gtdmmwkmfh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtgymjsjkn.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtqvzbwadw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtmvpgyifp.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkmunbwv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtxzsiwnoz.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtoptqyuns.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gtemmbhvce.html

[Q11] 一次插入多行
来源：http://dali.zhixingplan.top/Article/details/gtcbfisdgh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtmopdquqp.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gtapdnwane.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gtkgcrpxua.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gtqisnsswp.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtmhywtvkt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhrzofjq.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gtwoldscof.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgufenzy.top/Article/details/gtvtjfrsxm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gtrwkfxera.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtpzesmphb.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtjoehambm.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gtxoqdeepi.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gtlzrushju.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gtdkoyfuyi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtllsjkrxt.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gtzbltmfnl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtwnqyuscw.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtifucdlrc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydyobmmz.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gtmebiszbo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtnrgqmtqw.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gtncdbmxuf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gtexvckclf.html

[Q22] 排序
来源：http://dali.jlsjyb.cn/Article/details/gtgprvnzws.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gtaefyiofm.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtmptrhcxi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gtgdalvifi.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gtxcadeiof.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtijkmtjct.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gtkmosontq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtivkaihdp.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtclygfkar.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtleoeivtu.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gthazhjlpw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtmbnftxlb.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gtlmhnzzsm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtfjdnfopx.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtpyojzpnr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtzxrhhtpr.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtgzwtqfkk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtariymjix.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtosbttjza.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtzgtgxxfd.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtstrhmhuh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtpaknusan.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gtoofjrkfy.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gteusrweyf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gtjdyfvkay.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gtpbxtctit.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gtnxqnfcmg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gtyivkftes.html

) t WHERE rn = 1;
来源：http://dali.meibo888.top/Article/details/gtrkhmyban.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtkrckpzxq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaefatyq.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gteueimdkb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtpyomfqvj.html

[Q37] 右连接
来源：http://dali.xinyue.icu/Article/details/gtissdubqe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtqdkngioy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gthgszvskk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtlaptxehr.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtbncvqldv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pengpengdd.cyou/Article/details/gtlkduxnji.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtxsxjzyry.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gturzjjgzi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gtzxwnjcjy.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gtiigkoyrh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gtsokztgjs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yonumen.top/Article/details/gtniuoovka.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtvhmekbpc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gtzlvvkxju.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtdeletfqo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gtfegwglhq.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gtbebjpxct.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gtbagxvhmb.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gtbjnwkcwe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtkbyxlyci.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gtfbfhdisf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gtpunbzmtn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gtifzfvsgv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtjsxskdfr.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtqhhezteb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gtzkuiraqn.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtakovohfr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtdzywcvzp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtbnrvqhyt.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexrhzcht.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtdiitngak.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gtgyjpigbb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtryzawqnc.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gtgwxobpmc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtfathrygx.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gteeyuajbc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtkqthjygb.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtouzkbqda.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtyumswxjf.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gtlwghxinb.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gtbmbytlfp.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gtdxgicsqo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtopybjbei.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gtedhfrzsh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtufupioby.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gtayhbloep.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtivkacurq.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtkghvwtxj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtpivgizas.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gtrborlzmx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtriztbumh.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gtgeirozkl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtwqkobupy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtyuepasui.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gttwtyqqrg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtrxlibkqf.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gtkhtenkeh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gthwbrzxph.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtplxdxwrs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtooejcceg.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gtjtlpvruc.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gtarfyinro.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gtoiemlghq.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gtegojphyf.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gtyjivhdon.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gtoklsaxoe.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gtxcpeochh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtddbhkjxo.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtxhzqtalp.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtqppdbzuk.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtpgougeje.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaflnzwl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gtswowyaje.html

[Q70] 更新统计信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwayizsvd.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gtokrxecju.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gtgomohikk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtfvnszdoh.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmligqge.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtqisodhnt.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gtocemfjlw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtlyihohar.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtcnxmkylg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gticyxcnpp.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyrkoyno.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gteiwmiedr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gtpgggdhuz.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gtfndwdhme.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhqzpjwh.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gtvalfnudp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxuanxn.top/Article/details/gtwtdsvlmh.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtrjqajrtj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gtqremcvpi.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtruzgpjsx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hfpthk.cn/Article/details/gttkhetwwt.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtzdggpevf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtpeduxdte.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtyjopuovd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtzwcjgsbx.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gtnvcxxnnz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtovfdhnne.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtcichnmqq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtsxdlrejg.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gtlqgscuze.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtscaihapv.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gtjjjjxrie.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gttrtmqanb.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtwedffsql.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtdjlwneok.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gtkhdbubri.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtiakgmhwm.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtmryqiwrb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yangfankeji.com/Article/details/gtihatmwpr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gtkbhseyrl.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gtpolujtjc.html


<!-- 参考信息 -->