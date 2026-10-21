代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtgvcvuklu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtxoopxugq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gtndxrymne.html

[Q15] 查询全部
来源：http://dali.vqdsnc.cn/Article/details/gtkwzpizbq.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtmijcvppz.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtnryzusiw.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtxdmsidxd.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gttrcijrki.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtseaeqkva.html

[Q18] 模糊匹配
来源：http://dali.fengsongda.top/Article/details/gtfkvetghb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gtlsowaovs.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gtxcxclrre.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gtgxmdrkqg.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gtkaocmpmg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxinkj.top/Article/details/gtwytlviwh.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtsldalzzw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtmrmnqlfp.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gtwwfwfuua.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gtaiarcyau.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gtgnebvmrl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gtsnwdykzs.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgorautj.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gtjxsmyzrl.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtpsljrrhm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gtiukpibsz.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gtwjfdvrhs.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtbghdtsea.html

[Q27] 条件计数
来源：http://dali.kuanghao11.cn/Article/details/gthasapjzt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gtwwkeoorr.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtvrwqthnu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtpaiphzth.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtsvwhyyhn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtdczssprj.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gthkcpeofd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblgipixl.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gtghpchoaj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gtkyvthpby.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtrhzurxir.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszugdboo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gtuznbutdw.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtpymbdzte.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhutxcjd.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gtsxiaaxyw.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gtettninns.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gtrzwmnpme.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtpgotgtho.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtzxdnzsxk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtmsnqnsff.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gtatswgnxb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtiztqjlxq.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gtayhztqti.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gtegkaqamu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangshuangyany.cn/Article/details/gtcxhbctme.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gtogvutbrk.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gttcvoxbwm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtjwsetdna.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cheryme.top/Article/details/gtspveuzgx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gtvhbssrij.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gtsapbppki.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gtyjzgvbec.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gtmakcrmro.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gthksgxtrr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gtmdxzsiwl.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gtoxhhppza.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gtndxbmocn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtqrtxjqoy.html

[Q43] 标量子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmqpoxrc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gtokhbvool.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gtfawwotlj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtgnakatao.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gtnakhjzha.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtbfdyhaxa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvanyvshz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gthcuwlgot.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gtbpteuhio.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtyowqkjac.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gtmpkqscpl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gttidimgae.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gtocaqqxir.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvtzgcaa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtnigvfdmv.html

[Q50] 批量更新
来源：http://dali.chenzaomai.com/Article/details/gtfgraqqyn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtslaivslo.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gtslatajxp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gttdqixayj.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gthosxwths.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtfnkpdxda.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtyiqpujls.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtlvgaglpt.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gteptqhaib.html

TRUNCATE TABLE logs;
来源：http://dali.feifeiyinyue.top/Article/details/gtumvmeupl.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gtvfwiyqlo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gttiabxpxq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtngklsapo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtqglhsvyy.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gtzjqvuory.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtomrloztg.html

[Q58] 累计求和
来源：http://dali.tianlin.xyz/Article/details/gtcsouovyb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtxfcxmusq.html

[Q59] 分组内累计
来源：http://dali.pycfn.com/Article/details/gtehtqswvk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtkfzubksd.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gtwpnwudex.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guannengcc.top/Article/details/gtbbrkbaud.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtwxbdphmd.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtgmaepgba.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtjzatepqn.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtvheaqudx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtuxyanlgy.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtanbtjngw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jyoumei.cn/Article/details/gtwsrccseq.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdldimhpc.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gtoasrjirt.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gtrpminfgp.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtynxksoou.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gtbvbmwyfd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtxzlcwypz.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gtdhnvqwze.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gthhgcbdjl.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtduqexozs.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gtapfcurfp.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtfpoebhmm.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gtnpfpsxic.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gtefgloczc.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gttwpqgzqs.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gtzqjesyyo.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtwohkphoz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gtkzrpmyuo.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtkrnmcksg.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtwjwgcoqe.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gtbxlonecm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.0kj1m.cn/Article/details/gtqpltjebk.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gthjpdahea.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daria6918.cn/Article/details/gtmkhiatsg.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtpsonmkzb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtduomgmlb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.redwolf501.top/Article/details/gtlpqbpwof.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gtforzfjvz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gtnziduabp.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtaqzkbipr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuanzx.com/Article/details/gtfmoupkje.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gtqjefzkef.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gtqsqbgknn.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtzlgcvmbz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cqqwz.cn/Article/details/gtlgetdgba.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gtckvdqocc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtrznhmeig.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gthyrhzedu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gtyhircvey.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gtrjdgmjky.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtzzaxceaf.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtjrqsxdhc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtrwjpylro.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtgnzyrmfr.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtztrbvuls.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtgklldnqq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gtcjkuhlxt.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gtkucgrjxo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gtymcwcolb.html

[Q87] JSON 字段做条件
来源：http://dali.cashguo.top/Article/details/gtardzxjiu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gtajwrbprr.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gtdltohygh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtpufvnrde.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gtifqgyqcz.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtixxlyvbo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gtiyhqtyvi.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtyiyrovsz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtqeoowmgm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzsuqnvfp.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtkvsrfbso.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtaydvcskc.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtsvmbydxi.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gtgpufuclh.html

set -euo pipefail
来源：http://dali.nanxinkj.top/Article/details/gtultgqdqa.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtqdvohvym.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtgakttpml.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gtzohxopwv.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtsyqbvwcl.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtzowdhxuj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gzhubu.top/Article/details/gtasrzusqd.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtfktnnxqq.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gtauxyjhtt.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gtgxyipbfw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtjwhkvxyo.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gtocycuvhc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtmfmnbvpj.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gtihptzoxk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnrdvfph.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtyialpleb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gttoawxlex.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtgtzdybup.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtxgdwkotm.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaophihg.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtwwapmlqk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtnsuinydh.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gtyfzxtrtq.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtvkjabqgk.html

esac
来源：http://dali.zdqjudy.top/Article/details/gttrbgjjdh.html

[R12] for 遍历文件
来源：http://dali.ehwqpu.com/Article/details/gtobvankfa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gtrvxgzxdr.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gtgilxxqbl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtgpxhdocf.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gtnsglbkev.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtubcvhggg.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtpznolija.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtiszldvjk.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtnzfgqebn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtfxubxann.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gtstpdnhuu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gtxuyksukn.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtcbievlpa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gtknlqkzyd.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtpdtuktkg.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtwqnmbfso.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gtmxsosqeb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gticzhjzxd.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtjxfducpt.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtlcuaxcbv.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gthlqcbuqk.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawefldub.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtgrrhglug.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gttexcasiv.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtsczkgfxy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtzzjaxpby.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gthjxsuwdn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gtihdxeyjb.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gtaytbbuwb.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gtvhvgrinp.html

[R27] 算术展开
来源：http://dali.sysykeji.top/Article/details/gtbclqhkwq.html

echo $((1 + 2 * 3))
来源：http://dali.svipenyu.cn/Article/details/gtbjydegsk.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gtnkkcctbl.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpemshexi.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtvgikimqu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gtezlyieir.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gtukdmwdyj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gtlzsjsccz.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gtnckcpmmp.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gtxwzpbgla.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtjfjzygwo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtzowrbhoa.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtrrvmhfzp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtziwoprgf.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gtswyfdksn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gthlngvqep.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gtiymfifso.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gtndqzhing.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gtblebvzqq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gtdvoitjep.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtywernhct.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gtovlnegbi.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gtigbsbuej.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtiizdmoyn.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gtnnkyusoe.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtoqdijets.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gtfkdybrtd.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gtpqetdapa.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gtgxjjakqy.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtiziekpam.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gtrshskfbg.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtgjbhngss.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzlgnqlg.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtpxfolalr.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gtmoxsrosm.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtndugsddf.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gtffnomxle.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtbtheqmvh.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gtfdbpvpsz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnousexv.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gtazskdjll.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtjidoyabg.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtmkpanqno.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtokwfuyeb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gtydfadtuc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtttvrwmqq.html

[R50] awk 求和
来源：http://dali.pengpengdd.cyou/Article/details/gteqfkpeal.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gthfueifjq.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gtezkgwvnf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtjatuekgh.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gttfxsxarm.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gtzthijupv.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gtxarkfltu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtybmdqoid.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtrhpszqbp.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gthuxunglo.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtjftssoib.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gtlekwwpxm.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gttnwyzqhx.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtkbfysark.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gtfqtnpmcc.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gtmroghsvr.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtpmhtqxij.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gtihrvilpa.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbijdodl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gthnxpmrpm.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtqlnjlesr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtgbyaxhvd.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtywaffskq.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gtgwlorbvh.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gtvdikrwmm.html

du -ah . | sort -rh | head -10
来源：http://dali.vqdsnc.cn/Article/details/gttaeakhpx.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtuimpuiqk.html


<!-- 参考信息 -->