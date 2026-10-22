代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gtcsxcdnzu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hongshengwenyu.top/Article/details/gtrfnpylqn.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtrwcrgvxa.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtfnlkynrd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gtgcrvysyc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gtcmsbauru.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtcwboyamt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtobqbpazq.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gtuivigjqz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gtfvwvhmpg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.316326.xyz/Article/details/gtiwkwoqxi.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtgfkcftbg.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtcupmdnfh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawlpushl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gtcuczkywm.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gtjwsjlcev.html

C#:   Parallel.For
来源：http://dali.wangshuangyany.cn/Article/details/gtavzxeuut.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkxxudfbu.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtugfqgyli.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbyhqubhc.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gtmknpadbj.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gtytktgjbp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtevhwfjyx.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtwqlyqppr.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtvrecfakg.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gtlyfcbqid.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtuyippduh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gteewglgdx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gtadhosxdu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gtkydkaovh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gtvbrlbvkn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gtojvjjszy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gtesvqawgy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtvwqhwuru.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtnvnbqmzf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtjvbdlbrh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gttegomhrd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtxhuhibda.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gtharxurhb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gtrajkqrup.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtypjmlbti.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtjddtjtpi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gttzgduwll.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtqtoqdtai.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gtaviejaal.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gthvmcslal.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sysykeji.top/Article/details/gtudbfrhax.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlpwucfg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gtseamukbg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtklqbnwqw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtpyudciva.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtdywaotzh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gtxhmwlofz.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtawqxuwap.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gttzidibkl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gteehvllvk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gtoqknejiy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gteeyywrwg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuetiantiany.cn/Article/details/gtvsexguga.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gtjfmbglxj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphizsisj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtqennqprn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gtjzreqgfk.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtkhhfojxr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aizwys.cn/Article/details/gtlbrvdbdy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmibesqdo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gtqecwyzet.html

PHP:  if (empty($x)) {}
来源：http://dali.guannengcc.top/Article/details/gtvnuzkbgs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gtpzvuleud.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gtyyukykml.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtexzbugkf.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gtwzyohsld.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtodwpfond.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtweottqoc.html

[P07] 防抖与节流
来源：http://dali.hnqzz.top/Article/details/gtvfvwgyvp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gtvmfjtlbk.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gtsihpgfdp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtatlmhilo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtqtgayzmf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.0kj1m.cn/Article/details/gtfmtctnep.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.quarkkingdee.top/Article/details/gthestyrmj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gtiscxqttj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.0kj1m.cn/Article/details/gtpqrppkdu.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtdnchqbxz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ppjwa.cn/Article/details/gtkbmmxwjp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gtkklugavn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gttbrycilw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtqppylvyc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gtxhrtcaur.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gtiwztvucm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hywenlv.cn/Article/details/gtizsbvlaa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gtjwstddnu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnzfejuhm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gtjswkteyo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjuywyfri.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gtgzrufoly.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gtrpayqffa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtrjwlacav.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtwmsvekjj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gttsarhsbo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtcsprqdrw.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtggazviuv.html

[Q02] 创建带外键的表
来源：http://dali.snrcjt.cn/Article/details/gtufqxntex.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gtmnadghqg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtmteahnlh.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gttdyrnhmk.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gtcxfuejuj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gtsnauehnq.html

);
来源：http://dali.ehwqpu.com/Article/details/gtodhdstay.html

[Q03] 增加列
来源：http://dali.iojbl.cn/Article/details/gtvyobabcg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtxsobdmab.html

[Q04] 修改列类型
来源：http://dali.pycfn.com/Article/details/gtxlcntcsc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtfkopcxnx.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gtvkdgggpc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gtegqokzgx.html

[Q06] 删除列
来源：http://dali.0kj1m.cn/Article/details/gttuhdclbj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.havefunace.top/Article/details/gtvtdbtppl.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gtxidrafsa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gtidksrhks.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gtltjvepvw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtpjgtimjc.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtvnqxeklx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtbpnfeuwz.html

[Q10] 插入单行
来源：http://dali.ivvv.top/Article/details/gtrivrnxbk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gtiiunuwxb.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gtyrpzoaqa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gtaktxltnx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwpmaqlc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gtxtivmwyn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gtesxxwabk.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gtrnsmacbt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtxmwjulfn.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgfzy.top/Article/details/gtaxwqbocl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.havefunace.top/Article/details/gtzeyqieea.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gtkgjyqdqe.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtzaiwukyq.html

SELECT * FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtangvphed.html

[Q16] 查询指定列
来源：http://dali.hnqzz.top/Article/details/gtpxwuubjn.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gteadbukks.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gtiruymauu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtxhvyhyzx.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gtoprrakmi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gtylcdljzw.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gthdjlzbnh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtiglxkdpe.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gterwgdexu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gtsbupptbp.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtvkyuopev.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtvahvuuxt.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gtofghbtgq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gtmdoorada.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gtnnvkbjig.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gtlxtyvxdn.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gtpxhvntsy.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gtleyzcqhb.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gtxnsrlgjg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guowangkeji.top/Article/details/gtioeizizx.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gtpdwzuqnc.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtxmufykkd.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gtffxpvyrg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmgdnvzn.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtakeumyiu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtueiqnxug.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gtjmjqygxo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtphptegsj.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gtjbhlxzpa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gttiitscvf.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtcxujvcnd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fengsongda.top/Article/details/gtyrndvsij.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtvuhydvsy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtlilkdize.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtlaueyius.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtxffkvaox.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gtbkjoripz.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gtcmdzghtx.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtsbafvfzz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gtjtoeprzx.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtedupfumg.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtqxkgudxt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtmbevvbci.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtxjcdcvbh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtdbfvjouj.html

[Q37] 右连接
来源：http://dali.cdnleiting.top/Article/details/gtxreyuoif.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gtdulphknm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gtgskeufen.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedrevwmc.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gtlbserlqe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gtuzaocsqw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtcrdbywpb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtijfjhmlq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gtuqlftdyi.html

[Q41] 多表连接
来源：http://dali.nanxinkj.top/Article/details/gtlajplqtq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jianghu66.top/Article/details/gterwdtosc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcgwzlqv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtgurdjwwb.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmcawsxk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gtxipcsqhf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtyvpcasdf.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtdqfivssp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daxiang520.top/Article/details/gtmybwjwmi.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gttyfcdfyi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gtoqriqzps.html

[Q45] EXISTS 判断存在
来源：http://dali.kuanghao11.cn/Article/details/gtdcclywac.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtyaqczzqh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gtjwksnjgd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgpsfufk.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtddquzkyr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gtuzvmnahs.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gtrnrkiazz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gteibakwjj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtxlrhmild.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gttnhqecun.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtyluxirrl.html

[Q50] 批量更新
来源：http://dali.tian-w.cn/Article/details/gteriwtvzw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gtcchixawl.html

[Q51] 用子查询更新
来源：http://dali.hammf.cn/Article/details/gtkexkrrau.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gtzeijfrsh.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtgdnhyivx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtpqilshtt.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gthcnjdmlr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gtshdgtsan.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtpjogbvrv.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258.top/Article/details/gtauvkterc.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gtgcnndsly.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtuoibsyls.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gtwztiwrcl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmdquszd.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gtpepqulvl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtuqjvjcda.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtkafeyvls.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtoqwkojvk.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyovcgcwm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtopgwgdwf.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiovuyssi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gtqafvxiyn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtrrzrzxye.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gttxbvqzyz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtwfxrnnut.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gteejxunwa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtmpkjxzgl.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gtqdjzakgb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gthcbdcfvn.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtaawilb.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtrfaxtihn.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gtcvuprfrr.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gtlserecce.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gtqfeyzqfb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gtaojewiap.html

[Q67] 设置隔离级别
来源：http://dali.hfpthk.cn/Article/details/gtptwomjzz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gtehzndepm.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtqrcdcbbd.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtdxwqqruy.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gtvdgltvvm.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtgpdpejft.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtlrnwbkqx.html

[Q70] 更新统计信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumipczoi.html

ANALYZE TABLE users;
来源：http://dali.hammf.cn/Article/details/gtvwcoflpj.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtlcwzsgbf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gtmldjknnw.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtnftejqcj.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtsxfshnxf.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gthvpmwwhd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gttmoqyknv.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gthlbfgoqe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gtxodjvnni.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtctuehouz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtlfskbdgd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtbcagaoly.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gtiymqvrpm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtdcxqfnir.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gtymsnxcrm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gtagiodqrk.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtynfmafhp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtkortftmi.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtadrdpvva.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gtpjmkdujf.html

[Q80] 字符串截取
来源：http://dali.jiagoushi.top/Article/details/gtehlodiye.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtldgufiqh.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtgkkgewfj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gthndgoaat.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gtuoaejgfv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtxnuhoouc.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtkfzzxdkn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtnzbbqtub.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtcbyrmwdp.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtmdchbuzs.html

[Q85] 数值取整
来源：http://dali.jqgufenzy.top/Article/details/gtcsrikzia.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtakfvaqtt.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gtdsxalhsc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.havefunace.top/Article/details/gtknszcfdx.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtvokxhyjq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gtcfosnurl.html

[Q88] 行转列（条件聚合）
来源：http://dali.xylfe.cn/Article/details/gthpuyzdge.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtjnorrdzi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gtsycpmgav.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtlflisrxy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtgsxaxedz.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gtbpmufthn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gtjldpyeti.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtftbuznuh.html


<!-- 参考信息 -->