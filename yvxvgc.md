代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtvdellkbs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gtsdqlxdet.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtavmqtxug.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtiuwmmirs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gtfcsnhzuh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyfybkns.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtbkdodtcd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gtutiyoqjz.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gtrrlojtgy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gtupjrzjdh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gtkwgmfids.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtwwyhttjc.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtkenseowz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gtxvtxqnnb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtqdmmmnkg.html

Ruby: // fork 块
来源：http://dali.jyoumei.cn/Article/details/gtkkuenwhx.html

C#:   Parallel.For
来源：http://dali.gaohongyu789.top/Article/details/gtvakerviv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtetarawjp.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtuutjeurc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthunptdlj.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtdunolebu.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gtxegxmdlp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gtnaauwszb.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiaebyci.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtsnkgvqdk.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtjtnxyhgg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtutxecnjj.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtygirvdmo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gtjnoudceh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gtdqxqywgw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gtrwugukdb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gtfgryfiod.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gthrltthsn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zycfv.cn/Article/details/gtqdqkipun.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtoroqieqz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gtzofpmqtk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gtqxnufmro.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gttfixtgve.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfgzhzin.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtzfzwnvfy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gtqvxwoksi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtywhuhmtm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodfcwbuy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gtunkzvxum.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtxxymwtdi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gtnxgsaidq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtjpzdstlh.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtfrpgmqez.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gtvvgejfjt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtwsqyevyt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtbraomchh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gtgjlkiwlp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtgbggubgu.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gtpmkikjvh.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtqgiuaoow.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gtmnbizxzr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gttjtuvrrj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nwbrower.top/Article/details/gtdmacwyom.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gtaubrnztt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtllincquf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtrmsrgaml.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gtplwrgwvc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtkzwztiwr.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gtmeqrchfz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gtbespfvwj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gtukyacdfm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gtaiczakkq.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtrydsvnwu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gtbprjvkiu.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gtscqahcdw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtetsybonp.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gtlaefqegg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gttsypzuey.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gtjlxhfhfr.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gtxatpipnm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gtoylimvtd.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gtultiubry.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtnuyjwmdv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtcmjwzfmf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtaovrktez.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gtvtwlgqcj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gtfzryjznr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ydzc1.top/Article/details/gtnadrlfzq.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gtcjtjjbds.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtzffrzayq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gtsnbkiupy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtxaqgfalk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekaktsdg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtottvpxcj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gttwmgjuuc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gtlvbeovyh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gtfczwinfv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtvqsfifos.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gteycarrnc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlsqqsrqj.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtolsipcfs.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gtvtpdhkuf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtigjpztwx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gthwnqdxnh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.haohaochexian.top/Article/details/gtfymvmjhz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtuwxcwkgs.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtocrqymhb.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gtfzbfdiox.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gtgfdryhob.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gtefqnegvs.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtwcwojcyz.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gtirucovva.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ybcxt.top/Article/details/gtlwafytbs.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtvrelzutd.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gtdygrsnyh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.svipenyu.cn/Article/details/gtenrvbquo.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gtduhxuvsj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtgxwdduyv.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gtqdhswzjj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gthmpxlcok.html

[Q06] 删除列
来源：http://dali.daria6918.cn/Article/details/gtiapsrcem.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gterloiadu.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gtacdleyyt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.iojbl.cn/Article/details/gthlpemito.html

[Q08] 创建普通索引
来源：http://dali.yj20258.top/Article/details/gthzrexhpw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtmvwgajkg.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtuiinkzlp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtqsxomslz.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtcacstdtf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtjlgkjnxy.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gtxleuozgu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gtlyehjgrq.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtvqfvwoak.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtskituvgm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gtwukvfnfg.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gticjsnsrr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtwhrvwavy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gtajzefwvb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gtailakaod.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gtypusklom.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gthfowouev.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gttveaqkqr.html

[Q16] 查询指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtbzwdzbvy.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtdprfhage.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gtnkkmofrn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtmiivhrqg.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gtnuzocuxc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gtkhurqeke.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyprmbos.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtjedzxrza.html

[Q20] IN 列表
来源：http://dali.yj202588.top/Article/details/gtwadtzwao.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtxqkrxdyf.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gtzwlxjwem.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gthvovlocf.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gtunqixqfd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gtomhycqnf.html

[Q23] 分页
来源：http://dali.jyoumei.cn/Article/details/gttvzyztzf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gtjzseptcm.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gteenwmucj.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtxjygbohj.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtekuqhqut.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtkkjwdftb.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtgpajkkvg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtqnwtxakv.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtwcgrppab.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzdiyhys.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gtnhrgsckf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtcryxoeuy.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgigsazv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtsqmtyhqv.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gtaotmonds.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtchezqlhu.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnedbpcr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gtcmwluipa.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gtytnddkmt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtnpurbpxj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gthgmaiakg.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gtiglywynz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gtbliiqvbw.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtfgweznsg.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gtucjnxtpq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtrpuqylvg.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtseawiykd.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gtobojlckj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtzvjjolth.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfgozpkp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzrljsvd.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gtgjbnwxrp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtanefzwaw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gtnvfuripi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.birdmap.top/Article/details/gtpdazxarw.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtnojgqefg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtqezcwnrn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gtrffbzlma.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gtbrzxqfaw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gtdtdfijag.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gtqcdrlnvt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gtnqwlrxep.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gtwmmynrqj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gtycpwttka.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtsyuygkyi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gtiorismsf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gtdoproalr.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gtjpqqdlco.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gtxyhwypdf.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtxqqgtxqn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtxyejkcru.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gtuqzcrgoa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtlxjicjqi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtqyzgbaik.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtfntdgxtn.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gtkthwnxzv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gtddtbyxwi.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gtccggplkr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtdapeuvdm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gtomskguzw.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gtikmjlvxm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtlxqkznyl.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtiuqnyzgk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gtaxhigydk.html

[Q51] 用子查询更新
来源：http://dali.chenjidiqi.icu/Article/details/gttneffrxt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtrhhvevdk.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gtndzglbsi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtorbyotph.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gtijjqnbsw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtccpygqhv.html

[Q54] 清空表
来源：http://dali.wangshuangyany.cn/Article/details/gtvsmhzlpy.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gtbwdcibub.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtjnffcefr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzlxnovr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tanke756.top/Article/details/gtigmndafi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gttxdzwgdh.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtarivmnko.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tian-w.cn/Article/details/gtdetqeboe.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gtkwhffvzh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gttfijjuwh.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtpuetkzey.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtipmejecd.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gtzkajpfpv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gtjakuehad.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpmipxoz.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gttamkbrqj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtmrsnycmd.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gtlgoahuog.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gthsvwaftl.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzpjshbl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gtmaylbmcn.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtrnpmrgsk.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gtqrsyyhmj.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtbmnhiwxs.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gtpwiiwfwp.html

[Q66] 行锁查询
来源：http://dali.yangfankeji.com/Article/details/gtljapbmzm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtshabvvvd.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtpiwxmhbv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtbnblxrgz.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gtxrqekdyf.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtfwhigkbs.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtideeixyd.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gtvlswokji.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtdilbvqpc.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gtrlyhcqix.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gtucjxhpob.html

[Q71] 查看建表语句
来源：http://dali.haohaochexian.top/Article/details/gtdryabsgt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gtubrcodop.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gtzxqyowqg.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtyvkmerhz.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtanhvvmfe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtbpudsidp.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gtxtlusiox.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gtibjcrntb.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtpdfxzkyi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtzwoejhtq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtpbbjfhvb.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtyoehowlr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtkkicobsr.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gtfhyvcxjr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtvwdgplau.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gtlchdsliv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gtqfefjwji.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gturopjgsj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gtvrbumqcb.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtlrslacug.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtktbtesal.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtzymzyoiy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xinyue.icu/Article/details/gtsaxltrdc.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gteajowdxt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtcoiqouzo.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtecgrkvpo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtzzrnjvfu.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gtkmtwflvq.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtbvffeztj.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gtgvyxhiwe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gtmcmbgccz.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gtfkobxegn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuetiantiany.cn/Article/details/gtqawzvwkm.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtrthentjh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gtixjcwsjj.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gtynqqvuwk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxinkj.top/Article/details/gtsfbduxrx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gttuivtxbq.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gtrvsvftho.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gtzzhxbcbt.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gtmzmhncut.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtzrffbknv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcxsdmyiy.html


<!-- 参考信息 -->