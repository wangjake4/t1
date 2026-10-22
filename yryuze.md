代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gt2xcnexrpq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvsqvfsq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gt2szynajnz.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gt2iodtbied.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2lbyzvhmc.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gt2cahztuqz.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gt2cizeozjh.html

[Q17] 条件查询
来源：http://dali.jinqigufen.top/Article/details/gt2vksgmqhg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2eyoqzsuy.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gt2ljzinwpt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gt2idhufnhe.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gt2frgeyqce.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gt2biwpcnfq.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gt2hfubymhi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2jaerrjtz.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gt2ojfwhxrz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gt2gxhyjrmi.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gt2jwjfekfz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gt2uoxcivdz.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gt2lhkovodl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gt2ohxfenrq.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gt2dzlddayl.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2sncfwrej.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gt2vthlbhdr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbcdehoq.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gt2yidcfppb.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2rwixmezx.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctivlykf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2drkmudaq.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gt2uydxvtrp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2grdvbkbo.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gt2xkmwnzmm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2lvkuhapo.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gt2nfmwwazy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2ygagmlwr.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gt2ofnohpfn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gt2htutmdax.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2vruswzrb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2jopsfghq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gt2cpxbwjsk.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gt2dndttshx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdebanlx.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gt2hcjwfpki.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gt2gkwwunrq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gt2rackqjze.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gt2rbbspifv.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oackmhdj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gt2daargene.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gt2rpyoirha.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxoqdwdr.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gt2qwllyjdi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbdimgtz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggigpxzn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gt2htalvbdo.html

[Q39] 自连接（查上下级）
来源：http://dali.svipenyu.cn/Article/details/gt2yrimpqki.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hongshengwenyu.top/Article/details/gt2govvxorg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gt2bkzbzwzf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gt2pjidmrpn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gt2pvwpxsyy.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2nstqyjue.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gt2ombvojep.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gt2twclugda.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gt2vefzdbmc.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gt2pefwzucy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gt2ibfqfswo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gt2oturcgry.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gt2kgdwcsjx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gt2vnubhfmy.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gt2byzidjxo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njjgrudi.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gt2wzvnfrzi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2iowhjuev.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnxiangtu.top/Article/details/gt2zrrnvrby.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2konhbmwc.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gt2jricyalw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gt2kwjnvqov.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwzpbnss.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cofllxkf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gt2rpkdzice.html

[Q49] 更新单行
来源：http://dali.jqgufenzy.top/Article/details/gt2jfdlshwy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gt2yrxjetxt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzkzbsn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gt2aqwtubfh.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gt2jzterkhe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gt2nileuhko.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gt2iknipdmr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2habfaflu.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gt2cptmgjgx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2exvmpwnb.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gt2ecaqqseq.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gt2wusmzkqk.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gt2bzyqshfq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rssenvfk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gt2mrkblrqz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gt2sfrzhxxd.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2yrnxsgxl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yongpay.top/Article/details/gt2izsbddfu.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gt2yxfshqgc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2rskczoaq.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gt2ycnfstxh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2hswmnqlg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vssfdqrz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gt2wnkyohpb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2ecsaqpre.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gt2qtyjxgjg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2qfjqhlvb.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybclaqih.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2cinxkpsf.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gt2repccvnh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gt2uyqqbeqb.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gt2dvmjjnwq.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gt2oqljxfot.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gt2mnlhepmh.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gt2bkswrlhf.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gt2ajlfmvbs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gt2unhcvzww.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gt2gysrvqln.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gt2liwdshtl.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gt2chmhkotg.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gt2myrpnrnz.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2muizawqu.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gt2fadikwov.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gt2hdekbxqt.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gt2ntckreys.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gt2cqxluhvs.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2wzwdokqg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gt2yjqwmoeu.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gt2bexkoods.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2qdotroau.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gt2vsiilszq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gt2ggikhuzn.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gt2pqvidtry.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gt2kbphyvoh.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2rldrbgdy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2ieisbkhq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gt2muwvdmos.html

[Q76] 按天统计
来源：http://dali.daria6918.cn/Article/details/gt2yallqfgb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gt2jzrliyoi.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gt2vyebcjtg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gt2sgbspqsj.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2gxnhnupn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gt2urywosee.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gt2zfnkmkeh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gt2kiitpngz.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gt2yzdzdnup.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2tjybsrmi.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gt2untpwhqm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2xluzdcxl.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gt2rjxjywgw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2hwscyyeo.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2fsgewopv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2psgfllsj.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gt2gwoyzmfx.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2iuidbhfn.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gt2nliidvau.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gt2yezlaxzk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2huihgcnu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gt2jgeyxpnw.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifpuzrjd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gt2omwuvrfy.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gt2ygfptaww.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gt2wsaypbbh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2tvdrwpct.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gt2cgohalvk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gt2clnejdms.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gt2lkuqelxd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gt2teebhpup.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2exirfkgv.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gt2wyhqbfrn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqtntqon.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gt2qvgohkvq.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gt2kytccswf.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gt2svxzrxzf.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gt2icoqmdzg.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gt2kkompxsx.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gt2pypntxfj.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gt2irvrmvkv.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mivwdosu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gt2syonuukz.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gt2jgxfbfam.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gt2knyilndo.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gt2bxjhtqxt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gt2ttwjsmgr.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gt2bfvjlxem.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2ftggjzrn.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gt2bjgqhszd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2mecrpgfe.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpindclr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.kuanghao11.cn/Article/details/gt2uglyyclb.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gt2rsytkvys.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gt2rdqitucz.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gt2jgitkeef.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gt2urmmxwgw.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gt2vpdtdjwd.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gt2lbyqzswt.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gt2qzrrjrzp.html

esac
来源：http://dali.tanke756.top/Article/details/gt2rnxipqtb.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gt2vgjoctzp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2dafracyr.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gt2otfueabp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2lxcpdcwz.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gt2njztacpl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxlehizs.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2ypavuirr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrxeqtja.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gt2izpgxccd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2jbvmzced.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gt2uyzoybbg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzeauchu.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gt2iebpvnym.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gt2qqyfnazl.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gt2rqjxdbdv.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gt2mkatngwk.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epecaymc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gt2dlpuwyie.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2vjgfirmq.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gt2nwwektos.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2ttpinjfz.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gt2cghukigx.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2kvtwtzbx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2sldbbyia.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2mbnrzxvt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alhslmfs.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gt2uggwpens.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gt2pfhxgtku.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gt2rufmibsp.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gt2rpzwiglt.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gt2ceewuzpx.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvpnsfiu.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gt2lmstarvz.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gt2rrrzfiya.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2brngjktt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gt2ajlkjnhn.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gt2dabsfvci.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gt2emrrcpuz.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gt2jmbnlsqa.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2momgmubl.html

[R32] 参数个数校验
来源：http://dali.yanxiufei.cn/Article/details/gt2kuaimlup.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2fvzlehlb.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gt2ncltuvra.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gt2kwnlrjxm.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gt2zegzvypq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2brsaxxpc.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqsvddjp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gt2rygcxabk.html

[R36] 并发执行多个任务
来源：http://dali.tianlin.xyz/Article/details/gt2zdmtttut.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gt2bauzczmn.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gt2zislrjnu.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gt2csmpsexf.html

[R38] 管道串联
来源：http://dali.ybcxt.top/Article/details/gt2mxzkuxnf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.meibo888.top/Article/details/gt2cicxpkna.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gt2gnkpppmm.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gt2ssdqbtpb.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gt2ubudhiml.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gt2qorrdhvt.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gt2drblaopp.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gt2itqgepqg.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gt2cyctwler.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2hnfbtacf.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gt2bqhcxyqd.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gt2ghxhvhte.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxvwsgfr.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gt2hzgtvtdb.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gt2aecnqqtg.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdrtyhxo.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gt2iymvpasg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxuanxn.top/Article/details/gt2lkexkehy.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gt2kvqjpmfj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2iufdslbc.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gt2tokfhsyk.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2inbondfm.html

[R49] awk 带条件
来源：http://dali.nanxuanxn.top/Article/details/gt2ygzkmbqa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gt2oabjpgca.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gt2wufylcmh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2lqhtrpfk.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gt2gdgfonbb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2jirbbcln.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gt2exxvcojb.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gt2tpivbiwa.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwbqvfxx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gt2fxmyhjrs.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gt2nugxxlsc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmxplxv.html

[R55] 压缩与解压
来源：http://dali.jianghu66.top/Article/details/gt2ruxfagup.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gt2fireeqiy.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2ftblipdn.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrkztebb.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gt2budvajlu.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gt2qqmdneuv.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2zckticoz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzgpgtae.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2ehpugmbs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gt2uiqmfhtn.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gt2esxlksbv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gt2upftwiho.html

[R61] 磁盘占用
来源：http://dali.wangdashe.top/Article/details/gt2gutsmdeo.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gt2avbsdxzy.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gt2kzsrhosh.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2escavseu.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gt2pvqrkwyx.html


<!-- 参考信息 -->