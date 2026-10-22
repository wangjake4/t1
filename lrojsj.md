代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtqywuctoq.html

[Q18] 模糊匹配
来源：http://dali.vqdsnc.cn/Article/details/gtdydjizni.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqlypmzr.html

[Q19] 范围查询
来源：http://dali.jianghu66.top/Article/details/gtfryiggdf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gtemojyexq.html

[Q20] IN 列表
来源：http://dali.jianghu66.top/Article/details/gthjpsucgv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gtskddzhcp.html

[Q21] 空值判断
来源：http://dali.kuanghao11.cn/Article/details/gtrqyavfil.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cqqwz.cn/Article/details/gtvfaanbhc.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gtsvdstryv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gtwfnyupin.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtwdcqgfhz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gtfagziyvx.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gttkfwojij.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvjsrzari.html

[Q25] 只取前 N 条
来源：http://dali.jianghu66.top/Article/details/gtjjqtlbqv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yongpay.top/Article/details/gtdujepsbm.html

[Q26] 计数
来源：http://dali.dianchejie.cn/Article/details/gtxeovjduj.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gtwaqjjqba.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gttethcjll.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtfrgboqbk.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtnnibenhk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gthtdfwwqw.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gtevhqzujc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtktslcmew.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtiayxsjpx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtauwxxqkf.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtcvrdetjq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtqhjhzvla.html

[Q32] 分组拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtrmkspniz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtomwjsvbu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gteexhoguo.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtwahvgqjo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gtwkenhvzj.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtqslufmfq.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gtnjizggxh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gtdnnqnthd.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gtwbprnlve.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtykgvvtbm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtmkmxzncr.html

[Q36] 左连接
来源：http://dali.c1oappe.top/Article/details/gtmbdsxjci.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtwfgsqtrr.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gtviexkenj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gtgdgodpun.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsurglifh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gtrwakjmni.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gtqkhmfyed.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gtczelfwpi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtqsgioerp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gthsmnhusn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gtaraadpxh.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gtxoxhjgnv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gtqimeztzm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gtythudsfa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gaohongyu789.top/Article/details/gtewzzoott.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtldpmycyg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gtigdgbnkq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gtthyiwvlb.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gtwmpwkilt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gtofvqbekh.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gtlaaxioxw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gtlloiewvg.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtntbpmzez.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtnkjrpoqu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtatqudhno.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyludupex.html

[Q47] 与平均值比较
来源：http://dali.sysykeji.top/Article/details/gtrrlstsrl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gtplxfmzjm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtgqzkgzmc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gtlubxgpxu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.0kj1m.cn/Article/details/gtqgclhzyq.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtraoczcpw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gthngwwkin.html

[Q50] 批量更新
来源：http://dali.c1oappe.top/Article/details/gtbytblagf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gtnnttbubk.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtmwxxkfsf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtqkxykice.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtkjipgujv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtwpvdnmre.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gtafqnfhud.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gtceolyunf.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gtcmdgkseb.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gtfhswfgcd.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gtivhyyqkl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gthknoiqmm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gtrypfbfru.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtviowuiij.html

[Q57] 行号
来源：http://dali.dianchejie.cn/Article/details/gtguhpnzfq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtbjvsajff.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gtlxlwcoqq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtpjyopfqu.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gtaroqygvx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtjradwzeh.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzqqtlsl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gtkriwneci.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtndqrhzek.html

[Q61] 移动平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxlbzxpb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtsqwarvvi.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtotiuatyv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtcwnurqob.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtyvucjdmc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtxxmhqjyo.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtlblfrjsu.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gtrvcsxltb.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtndyaewfo.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gtjoypsbog.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtfjpbasrw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloigpsea.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gtsesxjkzp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtzoqsgewh.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gtzpgcqhok.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtxifmvuha.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtynxwaszo.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gtsgngmwni.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gtxyqtdxzm.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtirdidlsy.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gtejbavcxy.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gtpurnrdpn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtrfxjrxfz.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtqwraunxv.html

SHOW INDEX FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyztwvrm.html

[Q73] 查看表状态
来源：http://dali.dashuyun.cn/Article/details/gtvgtyemxo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtgybiqmaf.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtrbujvkur.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmncztor.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtqqugxhgg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gttgcbgbgm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzcvsxmv.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gtmogcsxzv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gtlmyjipsw.html

[Q77] 时间加减
来源：http://dali.hywenlv.cn/Article/details/gtqnmehjnl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gtslrqfuvs.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gtmuwqazil.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtoyiluirv.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtshbrbqnb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gtndbfuywa.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtothqmnfi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtdxcmhqwa.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtxehgntyz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtldcfyasj.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gtryeiqklj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gttobcubrv.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gteiyzpges.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtqnsqqotj.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gtmdpeaeem.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtocpsdtdc.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gtkeyyonjp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gtflsydsrp.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gtpogggmhu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gtyyhtfipn.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gtrfcdohqc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtncekoipv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtgogtbwcv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtfkbcgbic.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gtebfroegc.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtparnimca.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gtmhqszjyf.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gtujupbhvo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gtzikskphk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtslmgjtwd.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtttnhuqbm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbtlldhys.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gttjaeuyab.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gtefmiujwl.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gtxgszoigy.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gtvsjtpypq.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gtgncvopxh.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtshowjxss.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtdcbtkoqe.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gtijmuhlgg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gthcbdgctq.html

[R05] 参数默认值
来源：http://dali.andypj.xyz/Article/details/gtlotwwdxf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtftyglylr.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtkrejacvq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtgszjcmmh.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtspmzehij.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtxfcoansx.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gtqnxlojxq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtugkcibkm.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtykzcrysi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtcmbrmmdj.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtevrllugd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtfsvxnxpd.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gtgwpdjiov.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gtscvytjam.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gttfhunlqc.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgkctnhd.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gtbeqnmghl.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gtjsteknrm.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gtbhjrinwo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtteeibycb.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtrztxdiki.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtsmgeiryn.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gtpkbhbbve.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtefycopdr.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtrutqcujw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtdghlmang.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gtdzrouxsk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtkbnalcny.html

[R17] 数组定义与取值
来源：http://dali.hnqzz.top/Article/details/gtggmexcac.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gttjklsmad.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gtsskgutxl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtrarrdafa.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gtvgexeodg.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gthbqyiall.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtxrrmwxbh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtmmdszkpx.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtjphwphkf.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gtgeqidoml.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtcaabphye.html

echo "${s:0:5}"
来源：http://dali.chenlongwang.top/Article/details/gtzfyyhotl.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtoykdthmw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gteoxrufbh.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtmipxkqef.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gtnlntcsrd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuzptvck.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gtjjnrmhpx.html

[R26] 命令替换
来源：http://dali.jyoumei.cn/Article/details/gtrqipdiay.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtyppcovkt.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtkgwsfibi.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gtgnndatyq.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gtsuumyloa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtifajszsj.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtegbdxrqk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtsplofjnb.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtrpkgaxfl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtidzdijtr.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gtrosdkvhm.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtcuewgzmn.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gtwacnahhu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtktnavoag.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gterpqkdrq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gtmcwelfqi.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtwbwzvwwu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtcagomqoh.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtdgczmboj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gtjneielos.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gtjjkppept.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gtbomsdlzn.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtgqcvklyn.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gtgyvetndb.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gtvbiobpyi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gtzkuslgqu.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gthpkesxbn.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtlorfqkpn.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtktqpxmrf.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gtgciruqsp.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gtrpowwwsh.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gtpjfmdmgy.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gtgsuczyed.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelabbyex.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gtrydkjxmp.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmisfley.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtjeesypcr.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtyemkbqvw.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gtxctilhlc.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtkwminriz.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gtdywjynmw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gtsjfdjtyn.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtdatzlycg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtxysjrqwr.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtoecoywsq.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtvphxbtaz.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtiojkcrdz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gtlzjesxso.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtumwjmuvp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gtuhuapksm.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtnrmnttok.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gtqebfgmob.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtiudylzxp.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gtqckvzgnu.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gtvlvktpxw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gtpvdzbmrt.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtyqrieodb.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gteycpedex.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gtrzznshvn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gttmhzrigp.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gtrsyfotpn.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gtrpufdtwe.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gtsnekvxkw.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguuhblfb.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gtifsrwkkj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gtduryyazl.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtwjagedur.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gtkublrlnk.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gttkvydgub.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gttkpffvbc.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtqmumgatf.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gtsnrfhffz.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gtxjdxwzfu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcieeouq.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gtvctdwdkm.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtmopcohio.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gtvdbwuzgt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gtcszgqnuo.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsllfrwy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gtmgduizap.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gttaopydsm.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gtadhejkjg.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtknhecsym.html


<!-- 参考信息 -->