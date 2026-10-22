代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2capsxhdd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gt2fmehkvob.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxzspnnr.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gt2plxptdhf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gt2cvbdlegl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gt2cuzyygdy.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqmlwsbc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gt2vjeeielv.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gt2qicrhiux.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gt2sjdqqikt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xinyue.icu/Article/details/gt2sorwdcwq.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2ampvaofi.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmqbmjzx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhekign.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gt2pbvqcoti.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gt2nsuhxmdi.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czitnhkr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2zsgzyfsq.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gt2ucadkulp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2sblmugmw.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gt2tjwixvbs.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gt2mjhlbcxw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.andypj.xyz/Article/details/gt2rxcpbdze.html

JS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2qoeidvmk.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2ppqsbzjw.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gt2vxthtgbt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.c1oappe.top/Article/details/gt2dhkoxooc.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gt2efvhvsdx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlaskkmh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gt2hcoyejhv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuanzx.com/Article/details/gt2bzhwtipf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gt2zbbusyox.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gt2fognuflb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gt2mxvvxvbu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2yzekewnb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gt2hsmbhlex.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gt2tnxcpqmb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gt2abewjdze.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gt2pizfiqtb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gt2tpcbuvyt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gt2hhtscual.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2vpitefjf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvrebees.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.0kj1m.cn/Article/details/gt2nxwmipzu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gt2bjhswfcz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohenuzkq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.mhx1999.top/Article/details/gt2fuddnsti.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gt2utxlqpgb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gt2cngxzvdr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2nkzymkig.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gt2ufbpxaqo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhqjlkqd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gt2miugxfok.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gt2tspmzxji.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usrmsnyx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gt2uagqnqdt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gt2lwwxvobn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gt2srkepoyr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gt2nvjoqvcc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gt2mlbgkrwq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gt2aipdaxfh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gt2ujoxxtiw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2cqpyhtbc.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gt2ytvsnumv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpmdiugr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cashguo.top/Article/details/gt2mogvpzen.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gt2vikgslkq.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gt2hgyhuule.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gt2pgijowgn.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gt2mxpclajd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gt2kywyqngi.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gt2ybfugsql.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gt2dpjtyrhy.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gt2onrsgeuz.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gt2grarlzco.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gt2hivazhpf.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gt2dwbzecyl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2nuahgudd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2fdgthvvw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gt2xykocmrn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gt2urnbjzqt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gt2kcggdrwd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sufxvd.cn/Article/details/gt2obaounqf.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gt2eslxiyjg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gt2mpsfbpzr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gt2jfwkonmr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gt2iroxaixd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2mjavuwwo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gt2biatuyzj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gt2vjhuveja.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gt2xxclmflf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gt2ghwhdazl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2jekyznsh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gt2nupoogun.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpbygifr.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gt2oxmyzxck.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gt2ghlvgsfd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gt2sakedjkd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2esfqvnwx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gt2hgmpcjqh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yonumen.top/Article/details/gt2lwgtopro.html

);
来源：http://dali.iojbl.cn/Article/details/gt2lvtvjxdj.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gt2uvumhogr.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gt2yqpmhgcn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2dspemlsh.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gt2uoetkiel.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gt2nvkdkzmm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjxppmuo.html

);
来源：http://dali.yuxming.cn/Article/details/gt2eimqlmhr.html

[Q03] 增加列
来源：http://dali.gzhubu.top/Article/details/gt2qdksgday.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gt2yqhbtyqu.html

[Q04] 修改列类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twckbhww.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gt2gfwrbrim.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2yktfqvot.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yangfankeji.com/Article/details/gt2liyvyket.html

[Q06] 删除列
来源：http://dali.jiagoushi.top/Article/details/gt2rehxmnoa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cucudq.cn/Article/details/gt2zlcpidfu.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gt2ewnhwwmy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gt2whlfqift.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gt2wufrcegl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2owofoadz.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gt2nnjeavbj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gt2urptebya.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gt2ywgbcnbh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tvbmplst.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gt2rhvkuydr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgdkorbg.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gt2ejprrbro.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gt2dfjmhfkl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gt2xwgclyed.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gt2kytjooab.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2ovhgcrzs.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gt2zfjuiycc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gt2wbmwmzah.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gt2lxxeiwre.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gt2itaabvvk.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcgleryj.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gt2yvpcsjae.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2tkipwyzm.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gt2wchqnsjx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2wmwuhmuj.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gt2kpcvwsgn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.redwolf501.top/Article/details/gt2dvwjtcec.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gt2hilfvubo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gt2vngswboe.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gt2vcepydam.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2lhmdylhw.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gt2cjtwfpis.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhoulong.xyz/Article/details/gt2bdwtcysc.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gt2fvottkyf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gt2qtbjoamq.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gt2gohuxcqc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gt2phoxxmyn.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gt2zzfpjdfj.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gt2mwbpqvhs.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gt2ajnexbpq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gt2bzmflsay.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eghtqbgy.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2inobdvor.html

[Q27] 条件计数
来源：http://dali.sxryk.cn/Article/details/gt2evdqsrij.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2xmpmhgac.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gt2ecutcrvx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2sgcecbrz.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gt2rvvcwcab.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2gcbhxdok.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gt2bdcrhvve.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gt2nwdsehhp.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gt2dvhstghu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzopabxf.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2eknbckbx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gt2yajrxuwv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gt2tusbhkph.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gt2hiekzjml.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gt2ltkxlqag.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oedgkcrz.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gt2pxyvkcvn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gt2smctyqvc.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2pryleskd.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gt2rvafkpne.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gt2afoomnql.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gt2yhttucfh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gt2kwnagdht.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdhvucpa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssjznnhm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gt2mecwtuij.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gt2iyifpcda.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gt2dmfaavmf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gt2fbincolm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gt2aedrigzj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gt2tpgiokfi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gt2xijhwcwz.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gt2qfqgeqfm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gt2hbkqwmuu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gt2seiyffhr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oimkokiu.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gt2ehgptlip.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gt2rqzvqvez.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozohwaww.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gt2fohdsnzi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gt2xrpxfjls.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gt2bfnxeqek.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gt2ofjdohkp.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gt2xpgcatld.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2afhezpge.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gt2wvjaaldk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2xqxloghx.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfonayiz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gt2dpkxqlfy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2mzbgkswu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpwjdoww.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gt2czquqtxz.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gt2shnucvac.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2imbvpezj.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldunuqvf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhevmxey.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gt2neamxdha.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2vogamzdc.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gt2vaxricnp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gt2ffbtwrtr.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gt2ddkxpopb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gt2uwtxmvyv.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gt2zeiftimd.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gt2qzwlhcgg.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gt2myfncwsi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2oxnfmyoy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gt2qkbqyccs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gt2pnqkkned.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gt2ocsmltqp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2ojntsbkw.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stjlxqid.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2kdbknoux.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmeoslxz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2cuppcvcd.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gt2rvlyuedu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2teqvopgj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2tiiuzzwp.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gt2rzmtucae.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2wjvhzqhv.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gt2qkaumarw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gt2vqskrkdo.html

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfneovsa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gt2szsrbtcj.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gt2xvtdrugh.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gt2kggsffyr.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gt2jsajyblh.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gt2cihtcliz.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gt2arlneawy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gt2bteknmcu.html

[Q67] 设置隔离级别
来源：http://dali.zycfv.cn/Article/details/gt2cmvbkysx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gt2zsbgflsu.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gt2diylqikh.html

SAVEPOINT sp1;
来源：http://dali.cqqwz.cn/Article/details/gt2qwoymgvk.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2uhgitseu.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gt2uoyryqck.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gt2yyigroai.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gt2jqyngevi.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gt2omilrmjc.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gt2aktyfgpu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gt2ykvsnpzo.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gt2ptsbuduf.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzyyrrdh.html

[Q73] 查看表状态
来源：http://dali.zdqjudy.top/Article/details/gt2gjxzerur.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gt2suxsatsy.html

[Q74] 强制使用索引
来源：http://dali.ydzc1.top/Article/details/gt2vapmwhiy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2vofaaekd.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2aoaoibks.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2pjvsczyq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gt2tutidzvd.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gt2rlndwxnw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2gpafucon.html

[Q77] 时间加减
来源：http://dali.shangyingyoupin.top/Article/details/gt2blxuoomu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gt2ovbwscef.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gt2xwgfqzrt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gt2kjickfes.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gt2jvlzgybx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gt2tflkwwop.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gt2ogcuclpz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2pcwdxhtd.html

[Q81] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gt2fguufbht.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tanke756.top/Article/details/gt2zqjjquvw.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gt2evzqiabv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2flbzvtjk.html

[Q83] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gt2lupbdopw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2iwebquxf.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gt2brgomfub.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2kukpzecb.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gt2hfcufhkx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgufenzy.top/Article/details/gt2qovxrdby.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gt2kvyhmhwu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gt2klcczuuj.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gt2ojlsqeug.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gt2ppxhkyps.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gt2bzoylvkq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gt2ywlaeepp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2thfnleny.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gt2ouwxtsda.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gt2asqkcymr.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gt2hphajrii.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gt2xlbejgpg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2fucllmpk.html


<!-- 参考信息 -->