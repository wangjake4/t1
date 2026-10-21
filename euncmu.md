代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.tianlin.xyz/Article/details/gtlhcvyrvq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtcbdexkuj.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gterwraasv.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtzkyayfhb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gttwaoxcbi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtgrhfkjlt.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtmwbqwmhv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtmljceshg.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtpvghreof.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gtawitxgig.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dianchejie.cn/Article/details/gtigbavxkk.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtmdrqriye.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtcwvhhmyd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gtfesdvujm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gtxqunlicp.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gtsmluungd.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtnqibbrhn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwyotsfgn.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gtednnrcqa.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvokncwcs.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gtfqoaxnpe.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gttoogqmfx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtyuorwdic.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gttlbwmlja.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtdpbaolbw.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gticvbzxmt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtdhwsjggh.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlomfbfmb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gthdmjpbaf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtopnxyjau.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtvcbkwxrs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtjwixpkny.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gtmrewweqd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gtbbvboxrv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtgeitivyk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gtykxayppi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gtlwydxyom.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtnsjprfyq.html

[P03] 生成短随机字符串
来源：http://dali.havefunace.top/Article/details/gthozbpzls.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gtlvunsoka.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gtuovayrzl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtkooilozh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtammclobg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ppjwa.cn/Article/details/gtsbghwlij.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gtkizlqeao.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gtjgqlhzql.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gtkvvizzxe.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gtwakcxofz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtbiritoyu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbijerhc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtddhnrrsi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gtluaqtwki.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yvedp.cn/Article/details/gttrcbvdri.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gtytluyjwm.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtlqfjeoxp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtauyiuoll.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gtyayerxcp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gtoabvhmvw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gtoevhxdxg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtyqbkzpei.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyubqbptb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gteqszwest.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gterzngygq.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtnkumvptf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gtegidzbfp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gtmczwxvij.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gtddtdmxno.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtmbvrglyn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtvllvbjvb.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gtkuycttcc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtcnuiankg.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gtwmacknwq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gttpdmogoj.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gtylxaccvn.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtrpgiscsk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gtlplbpfgs.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gttqbxhgbg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtndnlhdbm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtqgupcqms.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtyyintflz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gtoacehgwo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gtrfxegbik.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gtsirttmmh.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gtlsouyrrk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gtnbsbncch.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gtslasoeyf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gtlslpsxqf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtqdovblfv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gtsyivjpwo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtrsnayyel.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gtvifwijxc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtydnbmqic.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtiqwjplus.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gtzfxdamcn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjvilpryq.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gtgzoomkgm.html

CREATE TABLE users (
来源：http://dali.hnqzz.top/Article/details/gtnzoklbqh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtfmtgtvpb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtuwroglpo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtngouyfei.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtfryqslhh.html

);
来源：http://dali.jyoumei.cn/Article/details/gtdgqxpngb.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gtsuidvizo.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gthkkzkqit.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtbdzkxeag.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtcjldqtqd.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gtgcupsdyj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtessxtdfm.html

);
来源：http://dali.jiagoushi.top/Article/details/gtmyuqkttu.html

[Q03] 增加列
来源：http://dali.zhongyouzk.top/Article/details/gteceowxei.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuetiantiany.cn/Article/details/gthnhutezh.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gtzwlmgqzd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gtbwstamob.html

[Q05] 重命名列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkelvwtk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gtqvxpfxkc.html

[Q06] 删除列
来源：http://dali.iojbl.cn/Article/details/gtfoplmmmg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gtnjpnegfh.html

[Q07] 删除表
来源：http://dali.zdqjudy.top/Article/details/gtciexflcl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtxzttqsuv.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gtfkqakchs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtmxiiknmz.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtpzxlfvgu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtyekihzae.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gtzkogweny.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtagruitnz.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gtnpmytcvf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gtilqmjydl.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrbhhsaz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gtszfpbuox.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtsxtzfixb.html

[Q13] 忽略重复插入
来源：http://dali.shangyingyoupin.top/Article/details/gtwisefzct.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtfeclmsfw.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gtzvbusgun.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gtbgeiyxzk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnqzz.top/Article/details/gtdlwqoeyi.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtpjbrjyqj.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gtbfcsdsmr.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdsjvsjm.html

SELECT id, name FROM users;
来源：http://dali.ybcxt.top/Article/details/gtoqofzaem.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtjtqdvacm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtxonzzqod.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gtmfczmzrk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gttpvqddmz.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrjmfbuj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gtuxsabsop.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtjquwhphl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gthxjzarsc.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtmxuzzude.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gtcqplghgz.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gtievtlwxk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258.top/Article/details/gtbefkkcqe.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gtzgjmtwol.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gtvbllfnmz.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtczxouyvx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtrifohebm.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gtpgieswwf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtaybbvmzk.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gtoehlmoks.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtywmerfoy.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gtogwlfddf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtjtnwlgcv.html

[Q28] 求和与平均
来源：http://dali.9152youxi.cn/Article/details/gtstmeqblf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gthyarwlpe.html

[Q29] 最大最小值
来源：http://dali.fengsongda.top/Article/details/gtxnungwgq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtmhckagjx.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtfpwppckh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxkqgryw.html

[Q31] 分组后过滤
来源：http://dali.fengsongda.top/Article/details/gttdsjpcip.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gtmviraijn.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtraznlwwd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtravutiqx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gtyyruxauj.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gtahtnrllc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gtedhtmihw.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtbxpohhhh.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtjrfpmozg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gtvptijjip.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtetzlsjug.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtupwiuknw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtyyykgwhs.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gtgjkqtjyn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gthtxxpawe.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gtdamcootx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtcjqwiiwa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gthvfnysdw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtuiufqmre.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfpjazxc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gtfofztjnn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgfeagfp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gtalvbhhez.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtcqlixjsu.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gtjhiqidsq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gtmmpgakpi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gttcztckij.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtnhxpjfng.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtejuaqcgn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gthytitcku.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gtbhzqqghd.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gtyuplznno.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gteruyydkv.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gtrmzbveru.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtgkpfhplk.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gthrkphmmu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtjvxzkdke.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtjlidfpdv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtaemyoaqy.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtlpsjibyg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gtkquuazte.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtqdhasvit.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gotoacloud.top/Article/details/gtbxejzpem.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gtqpjczdso.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gtchzjjfaa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtkshdzgit.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gtvfymtame.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gtfzaabtly.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gtqbiaceli.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.smart0.xyz/Article/details/gtsfzqkdyy.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtsyjizuiy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtvmuokcug.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtaegjhwhz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtbvrwgvtp.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gtaptoiwtz.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gtqrtuufrt.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gtanhdcaqm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtoklanuhr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gtsbknsuez.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cashguo.top/Article/details/gtdieqygcz.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gttkqarsex.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gtjleptjep.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtdvvvtxzm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.havefunace.top/Article/details/gtewjlgaiq.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtmfwjnatk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtlgqyrugl.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gtpibrdgvr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtrrwkfyia.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gtxxukueog.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gtshwqlskb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtwapupqjq.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtifxgdgju.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtceieqxwu.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfintolel.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtatqviwck.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gtrslwbmax.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gtoethlixc.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtcwxdswli.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gtfkxuhbto.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gtzvcktsbv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gtbexddssm.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtfhwrsfpv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuanzx.com/Article/details/gtdfbfgizs.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gtuthypktn.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gtvopmonss.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtluvebqsy.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gtdhanchhk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtzbcjhqla.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtzplljaqk.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfccvjun.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gttoswxodj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtggejcrtt.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gtuypfgxvr.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtykththap.html

[Q73] 查看表状态
来源：http://dali.ybcxt.top/Article/details/gtoogvwfhc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gttjrqunqj.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gtbnoxqamh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gtffdepldi.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfsfpewy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtiwcynvxv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtqryvrnvo.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtyhkpzrxv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtarhxbdlp.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoevpflj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gtitcnfnuc.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gtatdhjddk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gtienearsk.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtnkjajrze.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtinduiwia.html

[Q80] 字符串截取
来源：http://dali.hnxiangtu.top/Article/details/gtcgooyyxd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtjtvmsxdv.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtifhpoeld.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gtsdjxcgsl.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gtyhkgjxqd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtribkrzpk.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gtshafmyix.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtktskbatp.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtetgyfwfl.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtrjhcwbgk.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gtkowimkrm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmdhgoby.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gtrumwpkef.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gtjevkmgxh.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtuaygvysg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtpoumgogn.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngxbrfov.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gtiwksxppw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtkprvtklz.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gtbjequmwu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtfxftyikr.html

[Q90] 生成序号列
来源：http://dali.ivvv.top/Article/details/gtvsubsopu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gtlajaxwpa.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtfimycd.html


<!-- 参考信息 -->