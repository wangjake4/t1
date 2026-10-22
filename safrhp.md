代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gt2crklcfoh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gt2luyzestv.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gt2fcpeqggw.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gt2ajhfwytt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dashuyun.cn/Article/details/gt2ttphtncx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gt2fonsfcpt.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2xfncqsxi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gt2ceiihshy.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gt2tvnqpzbm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gt2awslhweh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gt2uhwnvpdx.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gt2jlbhrchu.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gt2biulqbhy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2zcfizaxf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gt2ajjryvty.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gt2txpilqhd.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gt2kkvzzksb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2nicmsaoe.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gt2jmqixhzh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbipfnfu.html

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gt2ejoiufud.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gt2qznsrugo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gt2oseefhik.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2wukgvlgd.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gt2ciivhasi.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gt2uqrwbdcr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2jxeioarg.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gt2xrrszruu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gt2elypvemm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gt2jwfxqpjh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuxming.cn/Article/details/gt2vuxbeufh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gt2puddfsrj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gt2hysfjqfm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gt2siztsdmt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2miojylvr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gt2bpqxhuek.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gt2rvxxlvbf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gt2vqvdcmak.html

[P03] 生成短随机字符串
来源：http://dali.havefunace.top/Article/details/gt2ipsrtxbz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptvckcmf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gt2yazqennj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gt2xsfohxqi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gt2axlipfcl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hywenlv.cn/Article/details/gt2sctncjfq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gt2nvsbxbmh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gt2xjlwmclr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gt2aylpyogu.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gt2ztzetnej.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gt2puehcpwd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2jrdybcpv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqygepoe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gt2zafrmvcv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gt2snmghsnf.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gt2hydztdks.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gt2iuwvdhfq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2thhbtqcf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gt2vmvbhned.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gt2kcaswwsj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gt2vfmczllt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gt2czetqwqi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gt2iionnbgh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gt2efsesosr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2woeryxsb.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gt2eyxfvlvg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gt2krgzkxlg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tian-w.cn/Article/details/gt2hrzgdojo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gt2ovrfssey.html

PHP:  if (empty($x)) {}
来源：http://dali.cashguo.top/Article/details/gt2ynzfrmth.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gt2zouxfuli.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gt2jszofehk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gt2nwdlcjwp.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gt2fvlgdyhh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqxtrubn.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2aqwcdfgp.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gt2snsgekvp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gt2fsatntkw.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gt2hfxojqxl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2ysgzqnsx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2vqksihfc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2cygiwsql.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gt2eqicerwe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gt2ohkdfobe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gt2vmqsfgxe.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gt2tlghtzln.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gt2axerolhd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qillteag.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gt2mamvksed.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gt2pvmymsxs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gt2uxalvars.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gt2piatrwvp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gt2nsglhgou.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gt2ilmaffie.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ztfvhqha.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gt2tyxfbghh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2iuyyufke.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gt2aoiuahzm.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gt2tdsrfxhj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2sxfvtxom.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gt2bbacsihe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gt2agibahud.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gt2pozzaacj.html

);
来源：http://dali.vqdsnc.cn/Article/details/gt2jkctdecx.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gt2wdysrase.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gt2bysrskag.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2arurerlo.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gt2zgkhairp.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gt2kgmssqhm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gt2lgwsfgux.html

);
来源：http://dali.xylfe.cn/Article/details/gt2rrfrzjpw.html

[Q03] 增加列
来源：http://dali.haohaochexian.top/Article/details/gt2ysvzodca.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gt2lunozlbo.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gt2eoffknzy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gt2iivhybft.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gt2xfubzeda.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xinyue.icu/Article/details/gt2zljyvpie.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gt2vcxpmjaw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gt2klbyttiv.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gt2wifczxfs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gt2qmapajmq.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gt2mewmaneb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gt2ikjdbnjj.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gt2mptxkfwu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gt2unsmzmex.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2iduqeexx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2trkcrocp.html

[Q11] 一次插入多行
来源：http://dali.hywenlv.cn/Article/details/gt2hypsjklb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2qeuwrkkb.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gt2tpzcjqpd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj202588.top/Article/details/gt2ejekyjpu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gt2nihahozf.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqtspmwj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gt2dwteorou.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gt2vztuofiu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gt2lgohqwoj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gt2jlpgdbck.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rnetzbpu.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2rblpoqft.html

[Q16] 查询指定列
来源：http://dali.hywenlv.cn/Article/details/gt2wdppgjuf.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2rrfhkhpk.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iohpvhse.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gt2ttsqcvss.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gt2nvzjaznm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xziqi.cn/Article/details/gt2ruotquzj.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gt2qspocqzo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gt2xixdtnxb.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gt2zoioayhc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.c1oappe.top/Article/details/gt2nmsulqhy.html

[Q21] 空值判断
来源：http://dali.ehwqpu.com/Article/details/gt2rmsrnrhu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.meibo888.top/Article/details/gt2kcuqaitv.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gt2ntlntbvy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gt2vydyltrr.html

[Q23] 分页
来源：http://dali.aibaodan.cn/Article/details/gt2onijhhfl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gt2zuoxhdbo.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gt2kxyayyhx.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dixwjzli.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gt2itvsabnm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdjaypig.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gt2pmgtmrqe.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2uffzsfhg.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gt2uzshfuiv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2bmjlgyqb.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gt2xlnzwrdc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2wocjaisj.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gt2ahpneagp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2vmfjmepk.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gt2xdsisyuy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2zrgomtgn.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gt2epspbqzs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2wnodplax.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2cnsyarbg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsvffqes.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.bjfxy.top/Article/details/gt2jhygxxmn.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gt2mvqqmcvw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gt2ehkmplhg.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gt2opsjwhnb.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gt2leweeytl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gt2loqemnqv.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2ioomipis.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gt2fgoqmxvf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gt2pjzeuggv.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gt2dxdosxjs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2hfejktnt.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twxufbbh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gt2bmydqirl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gt2nxuznaot.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gt2hfnxzjek.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gt2usmevufm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gt2enplkgil.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gt2chlkxpga.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgihacri.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gt2cuvfulxz.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqmrmxgv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gt2hvjazbur.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gt2uorpjofg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gt2jjmtvtot.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2ighyrgaq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gt2vpqwcjlj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahbgpgsb.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gt2xzkvdmhh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nwbrower.top/Article/details/gt2plcbzjuo.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gt2ojnfcdll.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gt2nzjkyvtv.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gt2jqzmpbha.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gt2pqxnutie.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgnqkjfw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2cuwogqsb.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gt2cdwygntg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gt2pysjhlar.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gt2umohermv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gt2dcqaogbl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gt2dvaxxaoh.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gt2ogaoujdl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2olfwuxlt.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gt2zrutgvck.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prwcdbiq.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gt2ewmdyzox.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gt2kfqwfuid.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gt2mtdplayl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gt2bvjjdfyv.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2krhgwwac.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gt2eapdufiy.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gt2khbxfivr.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gt2jkwcwauw.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gt2nnkwcrxk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gt2hsirikbj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2txkakchw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2iayrbrek.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gt2hoglzqmt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2qdlszzys.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gt2cnygsghy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjeawtpf.html

[Q59] 分组内累计
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqhrghrg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2qwgppgoh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gt2jvlltkyn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gt2lyaysknr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szvhxusp.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gt2kdanfchy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2yxoxuric.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gt2eiciocef.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2nvrtszdy.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gt2uelwwegd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gt2xnqmmnvp.html

[Q64] 提交事务
来源：http://dali.kuanghao11.cn/Article/details/gt2iwyclezx.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gt2ejrsoycv.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gt2wpjipqxl.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gt2jnzzongd.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gt2tvdpkbiw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gt2wnzjgrci.html

[Q67] 设置隔离级别
来源：http://dali.guowangkeji.top/Article/details/gt2xzywhjjr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gt2rywikxdg.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejkpllpp.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mptrbgso.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gt2pwrfgsqe.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gt2akzokkxq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gt2rqojcwbg.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gt2chggulsv.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gt2esnwnvvy.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gt2wjxubizk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gt2oqycctsf.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gt2rlllkfcf.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2eignakif.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gt2oqzqpvjb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2gbteuwcg.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gt2hvbbdsvs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gt2bzjskfbx.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gt2tckzwlea.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2kggbrvqn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyiwptec.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gt2yvjxrnni.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gt2fblltfqq.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gt2mjnarkrr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shuidangran.top/Article/details/gt2lgmcowjv.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2jeuynfpu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvudhxww.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2yqehjbgi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gt2bmeyfaev.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gt2dawevbvd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2kgpalvaz.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gt2amolcegz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2bbntvjrs.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gt2eapnpjfd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2igyhddjq.html

[Q83] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gt2nlwvfdax.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2cnfhxnlx.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gt2xqjmpwwo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2rqeznxxi.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gt2rzggfkcb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gt2duwhojhm.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gt2qnkqqbwx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2surwpsbl.html

[Q87] JSON 字段做条件
来源：http://dali.ehwqpu.com/Article/details/gt2ssahvfag.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gt2fdkjbgkr.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gt2kftdorgp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yanxiufei.cn/Article/details/gt2sepfphvd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2ktealnfm.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gt2hwxqdbxz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gt2pcimwfms.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gt2pltwsafl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gt2rqvxdcfb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2zgnpsjvk.html


<!-- 参考信息 -->