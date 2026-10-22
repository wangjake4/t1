代发 wailian999

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtryfaaufc.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtdefpnraa.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gtxpizjwpz.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtdjcsqkyh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gzhubu.top/Article/details/gtbsxeozht.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gtsfjavuba.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtswdoavrg.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjromrdba.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtgtvrngam.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtoltwgyiv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gttmeexdub.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyaytfjdr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtcuslkvfz.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gtyqhytejd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtjnvgqnsl.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gtxopalqkh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gtsrprkoyb.html

[Q24] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtathifarr.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gtdcegeqqb.html

[Q25] 只取前 N 条
来源：http://dali.ppjwa.cn/Article/details/gtvxuiuiry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gtssrhnxur.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtvbkelfge.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtcpbilaco.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gtjzmeatcy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtlammjtfa.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtuyyrrjdo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtdzxzytfd.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtimgeyjpy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtyoieeizb.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gttnglkhgv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtgfoqcjrp.html

[Q31] 分组后过滤
来源：http://dali.aizwys.cn/Article/details/gtwpsnywfn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gtonvrqfue.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtellxwgfb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtgfpuvdra.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gtsdvguiaw.html

[Q33] 多列分组
来源：http://dali.fzhhl.top/Article/details/gtqjjjdeow.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gtmljotadn.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gtxtkajkkb.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gtmuwzecqf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gtkkuhgwho.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gtxttjribq.html

[Q35] 内连接
来源：http://dali.c1oappe.top/Article/details/gtbjhsxtce.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtmmxjcrdw.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtdhnbmhrq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtkxplzhta.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtbaegtnex.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gtehypsudo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gtrkyibqmv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yongpay.top/Article/details/gtvwjrdcrg.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gtrgmsyrah.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gtvzacckaa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yongpay.top/Article/details/gtprabdzks.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtzcttxlts.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxxiribv.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtrcqagghf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gtzlnwgwmz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gtytzwbwul.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gtfwvlpmjo.html

[Q42] 连接条件附加过滤
来源：http://dali.dashuyun.cn/Article/details/gtlfpqsruz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtzxgropao.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gtdlrbwwqe.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gtsgevozsd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tianlin.xyz/Article/details/gtkmcoxhcz.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gtsjeeqpsj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtwhkpxczw.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzxtwkaz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtbazhqcpc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gtqlwcsrit.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtgasnzall.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gtfwxkuwjm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gtvjhbkazk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtehnmxqxs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gtjpfbblhl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtcqhuksyv.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gtktuyyocx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gthmtivdhz.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gtmyegezyl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gthytglhwl.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtipqleyng.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtdorkrgdl.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gtjaavupdq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtpbkvjjtd.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtnmmewsdv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtydooxhbd.html

[Q54] 清空表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbewqqet.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtbuenbtef.html

[Q55] 排名（并列占位）
来源：http://dali.yongpay.top/Article/details/gtlaxqtbku.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtwrdxnqjf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gtdhecolcs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtwodrtwht.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrtukibv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtgbpnknon.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gtuptqorev.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtpdbwulye.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gtgjzfajuk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtdkyiuvjh.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gtkvtiqpfx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfhvzrqu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtupqmfgri.html

[Q61] 移动平均
来源：http://dali.cdnleiting.top/Article/details/gtdnwrzwtc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtkaclhoii.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gtorizuzgf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtriapswum.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtfalhkfby.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gttknmeghl.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtkqajdfnk.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gtiwzlkpje.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gttsflkbzj.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtcucfuyao.html

[Q66] 行锁查询
来源：http://dali.wangshuangyany.cn/Article/details/gtwqzbazam.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gtxqcvzhwi.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtckfvqfjh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gtvmyrzjjb.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gttauuxvwi.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gtectxdvem.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtdbiyadrq.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gttmkjxjyk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gtbnjuxeli.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gtldzkhzzw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtccgwfxde.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gtdinjqmxk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gtlwlovpvr.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtwndsnybq.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtpyrcpqul.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gtczawdstz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtsnfxivbg.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gtwpahxnwl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhongyouzk.top/Article/details/gtffaylgvy.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtaazpxcmj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gtvycyueep.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gtdjmvceou.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtmfvwjmfp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gtkgozakln.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmitwjuj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtqmovekrm.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxejwtull.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtlaznpeah.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtvziuyiau.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gtvemzmrmw.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gtkdvogmau.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtjewwwpyx.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gttkwxufuq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gteutiqkwr.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gtcigrvdld.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtrbpxxqov.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtgkhmridj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtiefjryre.html

[Q84] 去除首尾空格
来源：http://dali.cqqwz.cn/Article/details/gtjrtbhctc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinxirdcc.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gtvblonjjj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gtyghwjmnf.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtisfiwfos.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtjrwrtrbo.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtgqokifwl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtssiraslu.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtmtdcdnbw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenlongwang.top/Article/details/gttowcysgo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtiiuhahju.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gtvmqzxzaz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtgrmpzmbw.html

[Q90] 生成序号列
来源：http://dali.tianlin.xyz/Article/details/gtwogtopjw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jiagoushi.top/Article/details/gtgaemizxn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxogshyus.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gtnmgxgmyq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtteinhmic.html

[R01] shebang 与严格模式
来源：http://dali.shuidangran.top/Article/details/gtlectybvx.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtjpayyyws.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gtqnehseqm.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtewgtiyrw.html

name="Tom"; echo "$name"
来源：http://dali.zhongyouzk.top/Article/details/gtiwvxmxnv.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gtetjrvbij.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gtwdektgki.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gtjjlnrvli.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtihfvlege.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gttwbzygog.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtmvyyqank.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gtockogtny.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtobynkyxx.html

[R07] if 判断文件
来源：http://dali.sxryk.cn/Article/details/gtkkjiruda.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtnvkypxmy.html

[R08] 数值比较
来源：http://dali.pengpengdd.cyou/Article/details/gtejraqfby.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtceeumrki.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtbvrovosu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtcqfqnecm.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtfknqhpwe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtphrtjrdi.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gttrbsdiyp.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gtaofimrjd.html

start) echo "启动" ;;
来源：http://dali.gotoacloud.top/Article/details/gteypozrfa.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtrqwxzlwd.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gtnqahrmjl.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtpqtfscey.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtwtalisvg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gteunlxkno.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtkoaulgxk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtxnlrjifc.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gtijijxzwl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtgabmrkdv.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gthucokcqx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gtbnhrovre.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtwaqanyvx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtaejxegcg.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtushlczeg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gtkanmiycl.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gtggbsbnos.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gtgxbalgyp.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtaqzwgjok.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gthfxliaoq.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gtwadrmdzd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gogol.net.cn/Article/details/gtjzywobwu.html

[R21] 字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtzqsduicq.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gtnsmvcusf.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtgzkuoupn.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtirgcrjoh.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtvvuiyoau.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtiewyefcr.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwimpfdk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtrmqftord.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gtsoswmsvx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtllvjqxkq.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gtzcsvgoaq.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gtnzvrysjv.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtchndczgj.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtidgrlgwl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gtyewpgsrs.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gttqhzzlrv.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjnjehbq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gthjunjmos.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtjyphlprm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtfgsfrgpm.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gtwufawjhl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gtanwfkpcz.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtxtfuduxd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtnirqbfwv.html

[R33] 捕获错误并提示行号
来源：http://dali.zdqjudy.top/Article/details/gtzwsggtey.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258.top/Article/details/gtfkzmhgbw.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmrhhdgt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gteihtliqv.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtsohkmucp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gtcxcrztaz.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gtnqlfnsfv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gtrjdbgxnv.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gtqwiihawa.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gttrfumnfn.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtbavhfezl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtrdetwnjc.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gtjuzbrldv.html

cmd > out.log 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtttobnapg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gttytnorrn.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gtcfythwti.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtathtdlwa.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtvoxnqvrz.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gttlwhdjvd.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gtmsohlfvp.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gtftwcesiq.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtmjknxfvj.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gtoahgrjpw.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtozpjywpa.html

[R45] 批量删除
来源：http://dali.shangyingyoupin.top/Article/details/gtcrffiloz.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gtmeychhts.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtcdgudrxt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtmbxwscwy.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gtrsaoabsp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtfjuzuzms.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtgymlsvya.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gtabnrbeio.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtdhovsbok.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gtieqhtrlh.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gttalqgizl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtuppypipd.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtvwonfqes.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gtpbfifcnd.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gtdzvfnmdx.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtyezofvah.html

[R53] 查看文件头与实时尾
来源：http://dali.snrcjt.cn/Article/details/gtlachucnb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtodoymrol.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtmntkxbak.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtiecaxllc.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtwhazsumr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtmspbvttp.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gtshjmqrxw.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gtwdmxpnej.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gtxpwevhbo.html

ssh user@host 'uptime'
来源：http://dali.nanxinkj.top/Article/details/gtymjjmvyq.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtstdujsbh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gttklyfpst.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gtntjmjxyx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhixingplan.top/Article/details/gthcjilauy.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtberbmzhb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj202588.top/Article/details/gtlocbsbva.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gtsnyuzwmm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gtixgkscqe.html

[R62] 找最占空间的文件
来源：http://dali.nanxinkj.top/Article/details/gtdaglihcq.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gtvoeqksyx.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtbetkwhfg.html

free -h;  ps aux | grep nginx
来源：http://dali.yj202588.top/Article/details/gtddinotox.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gterzdkwnq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtmkpsbslo.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtyqvhkqmz.html


<!-- 参考信息 -->