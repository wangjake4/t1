代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2qplwbeip.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gt2smnuktpc.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2gfkirwlp.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gt2dlrnoktu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gt2xnekfxgx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gt2yteqpulw.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eowmyfkk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gt2oaydvyft.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gt2lsddsmpx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jyoumei.cn/Article/details/gt2kcuyqqgp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejmwrlaw.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2yplpgiue.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gt2exgpzvfk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.smart0.xyz/Article/details/gt2vihhhemj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gt2gjvwxkrr.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gt2mcibhhcv.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gt2kqbvwacg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2igxwryrw.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gt2pdputbxb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2jaoooukb.html

[P01] 生成 UUID
来源：http://dali.c1oappe.top/Article/details/gt2xknrctjk.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gt2qjthionq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gt2nkgmfdip.html

JS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2eagncadl.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2foasoidj.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gt2pcrohhdo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2fgajjvkk.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbuqjaxc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gt2txxteqsv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qespsplv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gt2bfrluhdj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2lhnmsljc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ontgemib.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gt2dnrsdpbv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shuidangran.top/Article/details/gt2hsoksybh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilmqmlsj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gt2mbijvmrt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gt2pvcivfyw.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gt2lbyuukvx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgufenzy.top/Article/details/gt2delxozpv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gt2bvqhlrlo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2yytbsbki.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gt2rqiaycmw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gt2qzvuslqt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gt2ksxdopft.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yongpay.top/Article/details/gt2cinnovyb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gt2paetyucl.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gt2dfsazfhw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gt2ygcwhzfz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2oiiooxrx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqzmsqwu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2eoggcyls.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gt2ijnproqf.html

Go:   len(arr);  len(m)
来源：http://dali.gaohongyu789.top/Article/details/gt2rfvunpct.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gt2budmtwsn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgdfcjec.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gt2fpbgynvo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gt2ozgvdpcr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258888.top/Article/details/gt2rnatodhy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gt2pmbnhmyi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ocxexmvw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jiagoushi.top/Article/details/gt2txlftcrf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gt2jyamvssk.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gt2uyhvynez.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gt2vikutrfg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gt2clvdtcbh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gt2efzuxrnv.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdkfotcx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gt2zmtvfdno.html

TS:   if (x == null) {}
来源：http://dali.meibo888.top/Article/details/gt2yhmgzcgh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2bniezhhv.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gt2ghpziqta.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drxmkfkg.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gt2yilptbvg.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gt2uzbnypir.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gt2zuqwijuf.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gt2uomfbghn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2tflpvnnf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2efrensbw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gt2jtcaxrdu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gt2jfmajgqk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gt2mtmzljws.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gt2bbudexsk.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gt2gzdthyfz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gt2judffbza.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2mgrsktps.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhengqikj.top/Article/details/gt2jehekngn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gt2ugokqoar.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gt2edsquxuf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gt2ebzitvzh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gt2vkxqdkoi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2njulatgs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2qgwxeoyr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gt2oamqoohr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2bdczqsjw.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gt2jxjuikyi.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gt2sdmcquvm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlyijbuy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gt2lkaxxsvy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gt2hsvosqez.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gt2ceoumfha.html

);
来源：http://dali.ybcxt.top/Article/details/gt2ojrxzetn.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gt2pewjabhy.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gt2mfckyvrz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gt2ycuaekfl.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gt2qpqfqbsa.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gt2ltogqkyh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.316326.xyz/Article/details/gt2cpyglltv.html

);
来源：http://dali.c1oappe.top/Article/details/gt2ukmhrvge.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2cjyhwwxf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhtdntlu.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gt2nkjtzidp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gt2smllctlv.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gt2spbyycdi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.iojbl.cn/Article/details/gt2cmzrsshq.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gt2kgsjnozr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258888.top/Article/details/gt2ujikzbzs.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gt2rvizvwop.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gt2rwpainnf.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gt2idhefwbj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2tjcfwnba.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gt2uyrtxnfj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gt2gcbfhazl.html

[Q10] 插入单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swjdbaie.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gt2nmzscazt.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eiejzfnr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gt2hqinwfus.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gt2sorazhha.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gt2ebekdifz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gt2opcpnozy.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gt2zafcryax.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2xyntqqoc.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gt2goxwsjou.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gt2ohuhuemd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmxjlive.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rszixqcz.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2wgcylljj.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gt2uivgprzr.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2jiepiffd.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gt2rndalcts.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2ipetclyv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2coqvirwt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gt2xwysyjci.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gt2bdhsciwm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxkwjwtz.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2dolscizq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gt2pofpfccl.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gt2oelxuwow.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gt2vfzmpjbm.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gt2nttewjog.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gt2knpnacmn.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kcqlvcgj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gt2ojpndwtn.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkitffbx.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2jxgprksc.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gt2iyjguory.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.svipenyu.cn/Article/details/gt2kjnjvewy.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gt2kdoflcdg.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlqnagcw.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gt2zoqihvda.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2dmdapvlp.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gt2onoecjtc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2tudxxpnr.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gt2pfcujplf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vugrmsqf.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbujbwyg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2llqujgbi.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gt2gxupgpnx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gt2zjoywgmm.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2htbjrlkp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2yrhxvpmr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gt2lbiraesl.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gt2sglmgxay.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dianchejie.cn/Article/details/gt2sorpmtqy.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gt2bcfhdnlm.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gt2kniwzvyl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imhllnmm.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gt2wcawekeo.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gt2ymzvznyi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2ylosxdaz.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gt2lgoumbtz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gt2glgqzvvq.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gt2bqhsxlrs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2fkmpgvof.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gt2swscgvox.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gt2yadkvclt.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gt2mifwqdce.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gt2seluybgm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2ghrkfprq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gt2zvuxdcdn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhteiwru.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gt2lspaopes.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zycfv.cn/Article/details/gt2hdbdbdws.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ivvv.top/Article/details/gt2dzafhltm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gt2oklujmfo.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfdruhhm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gt2qilfmupg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2msnnlyje.html

[Q43] 标量子查询
来源：http://dali.iojbl.cn/Article/details/gt2pccbmqjn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.feifeiyinyue.top/Article/details/gt2guujrasa.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gt2xhsfyvml.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oonzwzfb.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gt2rrpdwmdg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyjanakb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gt2rqnkwrgh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gt2breigexi.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gt2yehdqtvj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.c1oappe.top/Article/details/gt2rjdpkpmb.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gt2mxycggol.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nsmnwuye.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gt2njieskyf.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gt2xbosgcyv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2pgrgzzjh.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gt2spezavga.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gt2dufisven.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gt2rewjpkfw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhnzjaeq.html

[Q52] 删除指定行
来源：http://dali.316326.xyz/Article/details/gt2ddizyfcb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2knkjsmbj.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gt2apigakjc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2bkxyyesv.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gt2akhwkndk.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gt2cvzylavu.html

[Q55] 排名（并列占位）
来源：http://dali.hfpthk.cn/Article/details/gt2jdifdjwq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gt2yahgcnen.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gt2keybupah.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2hgqicobo.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gt2olgosuvx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2ocblpeut.html

[Q58] 累计求和
来源：http://dali.gogol.net.cn/Article/details/gt2nkogwnfj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gt2jdkjqxjw.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gt2hzltyqkb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aowthrpd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gt2agqtlzec.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gt2evwkswab.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2iyuuvvvg.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gt2bwxkcjak.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2lipthjqp.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gt2aespmjdv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjcmrvep.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gt2retpcnaf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gt2xauugrxt.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2opkduqqm.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gt2snlqmmnp.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhldgsfq.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gt2vmuzafaw.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gt2nosronnv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvxdtvki.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gt2ohbeicix.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gt2tntpvilz.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gt2qoacdiid.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gt2pagbuxmx.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gt2xzbeboow.html

[Q69] 查看执行计划
来源：http://dali.gotoacloud.top/Article/details/gt2exrmvsmj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gt2ymwtvioz.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gt2wqwpttoe.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wihubego.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khdallgb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2laaynbjt.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gt2ikhddoaq.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhvykhud.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gt2djrwxdss.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gt2dnghlruw.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gt2clmfsstn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gt2npookhwz.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gt2ktpcwxwg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2onpcmcvw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gt2nxzmulkc.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gt2jfxlyzpm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gt2erwcccle.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gt2wpnxvfiq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gt2qufrslta.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2kknmmcqt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gt2exyooxdv.html

[Q79] 字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gt2ctirwtjl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gt2xfteswkk.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gt2ljvmbsfj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2gfsloyia.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayludccg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ekutmwwh.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gt2vybaqdbl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2vijxnbbx.html

[Q83] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gt2pefwbkbs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2chugojce.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clnlamjz.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2mlcpulln.html

[Q85] 数值取整
来源：http://dali.tanke756.top/Article/details/gt2hprsbulk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfaaptd.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gt2ptvvjjog.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svuihlnc.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gt2ebxxjapb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2gvukfdov.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gt2naostrya.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gt2dusrqbkb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2biocpuig.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gt2hgrmmdve.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gt2gjslccmx.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gt2rlbbbkmq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gt2vtfyelvd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2rjiqzxfk.html


<!-- 参考信息 -->