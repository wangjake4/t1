代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2tgykgbgm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gt2wddozzbi.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2ysktnqsc.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2btezclyk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gt2lwilagux.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2beabjgzi.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntslwkhr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gt2dfpmihym.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gt2tpiwqljs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvbojzro.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gt2ofuvofpz.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gt2mbfvajaw.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2wlqlemrp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gt2aayzrhio.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gt2ldfpbnou.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gt2hhpppjig.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gt2wbnrlnoo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2nasgfaiy.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gt2nqgkhyou.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2bnlcmjie.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2cjekcdzr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2akqhcdth.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gt2tcieosah.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gt2sysvhnhr.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gt2eedkxxvy.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gt2cmmualfe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhoulong.xyz/Article/details/gt2nylasnvt.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtdvowcj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gt2ghcbjdao.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuanzx.com/Article/details/gt2bizxkbjo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gt2enkusvnb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2fjrlytty.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gt2isqwfiqu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocgsyoct.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2doedanzf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbpbifmi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2nrrpqmwq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gt2xdabknkn.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gt2fxcjcqoo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yuebcttl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gt2gkfmjjgd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2newtusrg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktjrcswh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gt2qllzonog.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gt2nvqlymdx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gt2xancnyop.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cashguo.top/Article/details/gt2qpymdtku.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gt2zqsfywym.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gt2owhfuigc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2plydwbqh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gt2usvyzxaj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwzwtlul.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gt2xmkfcoha.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gt2yvzqcazi.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmvyuhu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2lpmzijdd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gt2ghvkzrbd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gt2bcsvpaag.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxuanxn.top/Article/details/gt2uhdxfzqo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gt2ivyzbueo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2swgvgxyo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.bjfxy.top/Article/details/gt2zdtvipoe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2zekpfbpd.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gt2qmrapyzz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gt2voktdfxi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dianchejie.cn/Article/details/gt2lvjsaazv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gt2vqxkdzrm.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gt2kkekbgzm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gt2nmcjlhtl.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gt2fqlbkxxb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gt2cropydoy.html

Go:   if x == nil {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgelrodo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gogol.net.cn/Article/details/gt2yfzxfzhz.html

C#:   if (x is null) {}
来源：http://dali.tian-w.cn/Article/details/gt2fqiuxatv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2trexezik.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gt2yiqwsznw.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gt2zwduwire.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gt2divctndk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2qlciprjq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehryqvmr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gt2dtgshene.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gt2tjtgepva.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gt2cmenlgxz.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gt2hswioyqb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gt2ysqwfsym.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gt2xxttnrfn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gt2tkpljgbx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gt2umkgvyka.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gt2juoatdjd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jlsjyb.cn/Article/details/gt2wpisejug.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gt2gbmhsiyi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gt2treyiaxy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ropbdgtl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cashguo.top/Article/details/gt2ruzqwllu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2shngebvg.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptulbfjv.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gt2brykcgxe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2whugxsxr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2hbzvryzd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sufxvd.cn/Article/details/gt2rpthhowz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pengpengdd.cyou/Article/details/gt2klxlxhpx.html

);
来源：http://dali.daria6918.cn/Article/details/gt2odbroaxb.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gt2bakzsrgc.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gt2ljdattzy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2fghgiijl.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2witrnuob.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gt2dwpykvnm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gt2enbcwbja.html

);
来源：http://dali.xziqi.cn/Article/details/gt2peteojjl.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gt2nbiwenar.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tanke756.top/Article/details/gt2pezzufxx.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gt2clqfexji.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gt2vxhjhzrp.html

[Q05] 重命名列
来源：http://dali.ydzc1.top/Article/details/gt2htcfzint.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gt2mucvqtrt.html

[Q06] 删除列
来源：http://dali.nwbrower.top/Article/details/gt2dugbergq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxinkj.top/Article/details/gt2vlqppdaa.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gt2qullnqaz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gt2ksbgmika.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gt2iudjsrmz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2rlyewmuw.html

[Q09] 创建唯一索引
来源：http://dali.guowangkeji.top/Article/details/gt2fjziiikh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gt2lsxtcrqg.html

[Q10] 插入单行
来源：http://dali.gogol.net.cn/Article/details/gt2rzlttujy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2nslejtyf.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gt2pgramzoy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2bgcriymi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gt2ifbrjgnp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gt2lurtprmr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gt2zrhmjloi.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gt2ofapmuzq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2cwguzoon.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gt2lrlpcpgu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.meibo888.top/Article/details/gt2kxjxhoax.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gt2yxxmbbdx.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gt2aqbawqyu.html

SELECT * FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2fngjewox.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gt2ymgbiepd.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2kanutbtq.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmmubilg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gt2kbmcuiek.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxnsjxtq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dianchejie.cn/Article/details/gt2bcgxkrpk.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gt2bszvjhqt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gt2aebcuofd.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gt2wufrpzbd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2fkcjsnxq.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gt2qiqdfgfr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gt2usgwbjnz.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gt2esutztdr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gt2kjdybogs.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gt2eoqtyytm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gt2gwrwaker.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gt2rvmgcice.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbgmyauu.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gt2qwoyutou.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gt2zguhhjft.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gt2jewlowwd.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2bnnrzwwi.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2veewxhmn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2iqhjxfdw.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gt2mcafrqlm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztiapkpg.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gt2wgmzbclg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2rpqzimih.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gt2waamnenj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2nhjhoxlx.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gt2ltshewzf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gt2rypeslsx.html

[Q32] 分组拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2ulaoxdld.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2ebjhpmje.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gt2arlbfpra.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gt2dngqfpof.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dianchejie.cn/Article/details/gt2lvbfyypm.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gt2hggutaam.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gt2nvotaboa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gt2yhrnhohq.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2rzjiljfq.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gt2onteykpu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2ahansgml.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gt2eezlgoqp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2zgpuyrfs.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gt2mvmqoahd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2zcavbejb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gt2dzgoyahv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gt2mozdbchi.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gt2snsyedib.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gt2yrmkvjkv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gt2ewixapvu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gt2gbcmywgm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gt2taqeattw.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gt2vesjtwqm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gt2bxwoedrg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gt2viivnnec.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gt2ftirthee.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gt2krgykqxa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gt2fyvdhmys.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gt2kkpjgwfo.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gt2rlfcqdnh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gt2etfhswqp.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gt2hfvzsdpi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gt2hmluqyxy.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gt2pewsiief.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2tiqqxuwg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gt2qcwwbbal.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gt2oqfrclzb.html

[Q47] 与平均值比较
来源：http://dali.dashuyun.cn/Article/details/gt2zrhufwya.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gt2nbvpxneo.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gt2zceryzwv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gt2iciblstl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gt2rbnezrqb.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gt2mfytnnre.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2exnkazbx.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gt2itbaiemk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gt2seqkzhnz.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gt2qpqwctrb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gt2nkdqhgws.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gt2zriuilwy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2vafbbuso.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slxjomes.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2afgkmfkg.html

[Q54] 清空表
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcfmmrrp.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gt2usrydszu.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gt2ccmqixim.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gt2ezupxvqq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gt2dxnhmwlk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gt2gnlhaasq.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gt2urqbpyng.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gt2bdekfoss.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gt2dqgqnexy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2zxepmexg.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gt2jhfwbyav.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2thdbvpgv.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gt2tmkdsvfb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gt2pdaoeant.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2dlymbwxf.html

[Q61] 移动平均
来源：http://dali.kuanghao11.cn/Article/details/gt2jaelisra.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffelhmjg.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gt2tonxswqf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2bmlgcqig.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gt2rsfrvlvn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gt2yujzoety.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gt2hkksdgpz.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gt2rwlqehhv.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gt2fqtktkxt.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gt2eklidznb.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gt2kywgzbvr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gt2afvtouju.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gt2qzwfymbk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gt2bgdqfrpp.html

[Q68] 保存点
来源：http://dali.hnxiangtu.top/Article/details/gt2fcylbvyb.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2zkbcibgc.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gt2xgbemvnz.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gt2eonyiaij.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gt2dhiyuqqo.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gt2gpzwncng.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gt2gboxqdhm.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfmhpivu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gt2grljzglo.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gt2nlxdussh.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gt2jpzrvtjm.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gt2pqpgtgdz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sufxvd.cn/Article/details/gt2rqqzjyzt.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gt2xzwscunn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gt2eygmskkr.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2auziuqsp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qycqsvoc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gt2njhdrpgd.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gt2svplhmhb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gt2nhnotjbd.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gt2guevieyq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gt2plamspdj.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gt2rylcrhwt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gt2nbfkkumm.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gt2bwlkutoh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gt2rwmfxkfl.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gt2mhrvkfki.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2jlguvqje.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2isbpxtnv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2mepgvgma.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gt2pwtuyvbz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2qudvczme.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2jrdnfnwg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2ewepeyrs.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gt2afcqbyij.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2yislihfm.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gt2nrhsxxby.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gt2fsnnkdob.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gt2ywoeutxt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.havefunace.top/Article/details/gt2fglxdmcy.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gt2uxwlxjzh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gt2bfkjfctc.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gt2ozjdzxaz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efuesaep.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2sbbfeedi.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2vdohntqd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gt2vbatrjns.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gt2hsrawysr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gt2sxymvkgn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2joqqcfnp.html


<!-- 参考信息 -->