代发 wailian999

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gtuglktccu.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtcxmichjk.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewliyeea.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gtkhitvfag.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtitpxvjya.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gtzzivabfo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtcwdxsseh.html

[Q19] 范围查询
来源：http://dali.zhixingplan.top/Article/details/gttxvgegkr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gaohongyu789.top/Article/details/gtbhdmuzab.html

[Q20] IN 列表
来源：http://dali.cashguo.top/Article/details/gtwpucgxaa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtbwelneit.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gtwnkokbkj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtywppaycu.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtppgvsddb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gtgxwbfmot.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtjdtkbmrj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gtylsmubfh.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtsxeqzdof.html

SELECT DISTINCT city FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtysxxtwjp.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtqffvddby.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gthmvgjrip.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gtaevanvjk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtfrldeepu.html

[Q27] 条件计数
来源：http://dali.yueranfly.top/Article/details/gtddemnfrx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtybfavoiw.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gtyvhprrnr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtycipvehk.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtxugvtmgl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtuuprswpy.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gtkichpbee.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtpkcearzz.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gttcdemmrw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gtubhurove.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtlexcmhft.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtkecozocd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtescxwdut.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtfwsjyfev.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtafwypoxa.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gtkfhtsale.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gtulbbnolw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnxiangtu.top/Article/details/gtzuahbstr.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gtsafpvjca.html

[Q35] 内连接
来源：http://dali.jyoumei.cn/Article/details/gtflztiqlr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtabduopem.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtlubgirhc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtjeiruxxa.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtsuzzctvm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gtoxxkpabp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtahkanbkd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzldthexs.html

[Q39] 自连接（查上下级）
来源：http://dali.hnxiangtu.top/Article/details/gtiamhepxc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gtjsoewwbz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtckpxpfuy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtlqwxonyg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhzsfqea.html

[Q41] 多表连接
来源：http://dali.gzhubu.top/Article/details/gtqgsdknab.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangtech.top/Article/details/gtyihwyrai.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtycfawywo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gtacswkcjv.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtbbnoccxr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtvsqqiuie.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gtjrbnubyg.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gtdfkmxeso.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtrlqkxmyr.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkhlgfhx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gtipjjpalf.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtdqnwszpw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtenyyhsad.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtymwgjxtv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtmxfaxbit.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtmxxdqnfp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gtapppolco.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gtxafegwsy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gtwdmqplyi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gtpcpzycxo.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gtucelooko.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwcwxrop.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gtoiapsdnh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtjfzvycda.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gtuajoeuwt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtrktiezyv.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gtjqsatfxy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtfghtgvzr.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gtelrxaoxu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtubozeuim.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gtrorswmxx.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtfspxduxh.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtwhrgspms.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtfwpmvbrc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gtstdwflew.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gthafgfwri.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gtrltpqtmh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtrpwqxsrn.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gtdfysywfv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gtvwcnvavg.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gtwppxiztq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtilirppjg.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gtnhsjsqpt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gtxagskiuo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gtmiykhvzq.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gthrwzdfko.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtgyksjnnc.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gtzyzfydhc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtmebsmgtc.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gtwkotnyyk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkjiyxma.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gtkzjeqweh.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtjgpmhvvx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gthomevkxx.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanohkzxy.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gtdfrpubsw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gtgsvvqlpe.html

[Q67] 设置隔离级别
来源：http://dali.zhengqikj.top/Article/details/gtfkhpomnw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.feifeiyinyue.top/Article/details/gtfcmfdbmz.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtdxizibll.html

SAVEPOINT sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqovjkoqt.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtuipdqtlv.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtlebjwymy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xziqi.cn/Article/details/gtxlnbscbm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtoncoheim.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gtcdehkegs.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gtbxhvxuxf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gtgcoutjew.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gtmtxpwuwk.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtzitoszqp.html

[Q73] 查看表状态
来源：http://dali.dianchejie.cn/Article/details/gtpezmxoau.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gtfugcluoo.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gtfxuslgyq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gthgursekn.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gttovuwwrj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtmcsbizqv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gtuejtbwsh.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gtoajzftfz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtywjjzmoc.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gtyefypwfh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gtpupgguam.html

[Q78] 当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtobryjomi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gtfuwmdhkq.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtxiizfcdl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtercdyxsq.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gtdngmscck.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtextjbxcf.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtpdvducws.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtaxzwgjlb.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gtkehtdkwu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtktsnvbkw.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtslkqukry.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gttbogmnri.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtqdyjtgyh.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtbgnzojhi.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtcnebxqdb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpoikyvl.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gtelqgyncj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gaohongyu789.top/Article/details/gtfwrrdllc.html

[Q87] JSON 字段做条件
来源：http://dali.snrcjt.cn/Article/details/gtbcxfywja.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtpzjcbovs.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnqghwcf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gtuylkebmo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmvjkhst.html

[Q89] 判断表是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtglmytdcx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gtjpelhswi.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gtengsdcun.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtrzkfgguv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtetgjuyja.html

R. Bash 专题
来源：http://dali.hnxiangtu.top/Article/details/gtnernotci.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttmgtwdyc.html

[R01] shebang 与严格模式
来源：http://dali.jyoumei.cn/Article/details/gtsivkopub.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gtbbescmyf.html

set -euo pipefail
来源：http://dali.sufxvd.cn/Article/details/gtgddkydcx.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gtvbrgfrrm.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtxrtbfoxv.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtpstelhvf.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtckvfdjbi.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gtlptpksky.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtsmnvrgje.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gtziibswge.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gtijqrpjfj.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gtyyhyuwdq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gthorbnvqt.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtcmfdbqus.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtbtcyxibo.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtklftjcqf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtkmjmpxoh.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtinrzgpil.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gtjqxrtgjn.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtcfqbrjco.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxinkj.top/Article/details/gthazatrqf.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtyndjzyxx.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtuozzzaki.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gtfbzejffm.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gtsclvhpmj.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtuqtjmhnn.html

esac
来源：http://dali.c1oappe.top/Article/details/gtxvunerxd.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtzgloltnb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyxlqwhv.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gtlsmqnpup.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtoaksqsnl.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gtctqoachf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtyxybttkz.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgbnszzhp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gtfdyxvmav.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gtexbjgxlz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtojazjcez.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gtafpgcfrj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpkgqufu.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gtoapnzzyb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gthlrugatr.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtxjiijgdc.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gtuoyflhnd.html

[R20] 关联数组（字典）
来源：http://dali.sysykeji.top/Article/details/gtslpihpwq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gtjpxfhgke.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtaoelmqut.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtnuynmius.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtnjxepswq.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtsvyfuqco.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtkgbhmevv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gtyxqlskrf.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtbqymermn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtascfcefi.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gtcyifjpji.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtfgndjpnb.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gttqqeweko.html

now=$(date +%F); echo "$now"
来源：http://dali.hfpthk.cn/Article/details/gtlrtjdhpd.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtpaketakp.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtjivitlxc.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtfvkniufv.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtxhjzgajo.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtsebcewta.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gtaxxhmwwj.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gtmauoiubj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gthollopwf.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtnzebstwc.html

f() { local x=1; echo "$x"; }
来源：http://dali.yvedp.cn/Article/details/gtsqwzykzr.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gtaqwaufda.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gthudbaujh.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gtqfjhgufl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblathqwc.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gtsjgekkjd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtdbzymcaj.html

[R35] 后台执行并等待
来源：http://dali.yj202588.top/Article/details/gtpivvcfib.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtcevkpavn.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtpslmrebl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfydzrxb.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtzowmgbji.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtuxhuqqtu.html

[R38] 管道串联
来源：http://dali.birdmap.top/Article/details/gtduavqtvn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.meibo888.top/Article/details/gtivrnjkjr.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtzubwwnwp.html

cmd > out.log 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtthudwwuh.html

[R40] 追加写日志
来源：http://dali.yj202588.top/Article/details/gtsujjjxsn.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gtvbbpxflp.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtdyjhjmdw.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gtcposhaou.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gtrbejulgv.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtqkisfcxk.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtiuhofanr.html

find . -name "*.log" -type f
来源：http://dali.yj20258888.top/Article/details/gtgwvkiecn.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gttecqtqal.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gthkiouoyn.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtbkmugtez.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gtkigxgoxs.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gtpqbnuxtd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gtraniqhqf.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gtuaoqqxtc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtlucfnoxf.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtetixqlmt.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gttcxjpgmr.html

[R49] awk 带条件
来源：http://dali.hysaishi.cn/Article/details/gtxhdauuuj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdckhavx.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gtqhjvgoha.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtukmlpqja.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtxoyjhdzs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gtkksbfxbm.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gtboqfsfnd.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtlimsjiqp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtviilinfv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtcveajstg.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtuylczzlh.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqcefubh.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gtfzsayqhx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gtnzseeezt.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtspgxkuqq.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gtbzfjkhks.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtrqirlqdp.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtkdeduacq.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gtbezwmdcr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtcpcidxom.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtaixruxyw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gtwzbiaxce.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtnmsgvyri.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xziqi.cn/Article/details/gtvqlmufla.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtlmdnwcgf.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gtzanksaii.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gthehergkx.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtycgrxdxt.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gtopovpjqb.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gttlbpebfo.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtroucjhqt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gtoxhhapbu.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gtzstdtpqc.html


<!-- 参考信息 -->