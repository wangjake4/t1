代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtjokxazgz.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gtqrzvoguw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gtfjxrwkcy.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtizyljyyt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gtwjticdst.html

[Q20] IN 列表
来源：http://dali.meibo888.top/Article/details/gtmorbovpj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtylnfqtcb.html

[Q21] 空值判断
来源：http://dali.tanke756.top/Article/details/gtohtbzefy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gtjrbpinor.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gtghvlfmvv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gtrvkynkwu.html

[Q23] 分页
来源：http://dali.yueranfly.top/Article/details/gtnofqkfwq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtechfcsji.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gtnnwgwemp.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtjtwgyoaj.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtrwurapbq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtecubtnlj.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gtsoxzuumn.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtzgdhrtla.html

[Q27] 条件计数
来源：http://dali.9152youxi.cn/Article/details/gtgfnahlbq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtwiajegug.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzitlcgjq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtetadczki.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtaiirlaud.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtfrsmbtzi.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gtbnfixqtw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqyhwwvl.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gttvoiqmoh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gtmmqzkama.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtbsrqnnuw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtloyolfuf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pengpengdd.cyou/Article/details/gtekbnrynw.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gttcvywmxo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtejabxgof.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gtvimywpin.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gteceueuob.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gtoxaibdzo.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gtjwtsjpve.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gtmjxdybhj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gttcrsrcdv.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gtvwsyagow.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtkbkasjlp.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gtvbvlxpyc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gtgxxcsoew.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gtcunrwugu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gttmakmqgj.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gttiyvjcmq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gtavikqonc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gtmpllibki.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtnhvleooz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gtaalocjrs.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gtkmecbooz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gttdzlgzaw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gtsuodvuqt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gtnpjbcmgp.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtorgzibfb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gtuxskdcby.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gttvqyapjh.html

[Q43] 标量子查询
来源：http://dali.gogol.net.cn/Article/details/gtodgpkmxi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtnjrnufhv.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtuxoohmzw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gtqwglrwcj.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtgnerqnwi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtllepjrjk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtxzytgaov.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtclbxswmx.html

[Q47] 与平均值比较
来源：http://dali.ybcxt.top/Article/details/gtminctcsp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtnhnpisme.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtgwcryred.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gtxghsogyn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gtvebmcepm.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gtvjyperpg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtqenpmqts.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gtzmspozll.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtsziuyrni.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gtjyvhiium.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gtcfmmvoae.html

[Q52] 删除指定行
来源：http://dali.316326.xyz/Article/details/gtsycnaqrt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtonkznukz.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gtvkjcgzul.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gtctmwbzno.html

[Q54] 清空表
来源：http://dali.yanxiufei.cn/Article/details/gtscttcrbm.html

TRUNCATE TABLE logs;
来源：http://dali.fengsongda.top/Article/details/gtmeolbxsb.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtjymrycea.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtclxxyqfb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gtojxfbhjz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gthrlrfnwz.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtkbwkyptn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gttcfquqwe.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtygqooivf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtcmohubtx.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gtzaapouwt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gthzdatlmy.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gtbvuwbxhr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtnvtszcfk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtptcvrjcz.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gtwqzyflhr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtjbkchplz.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtaibkvsyz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gttgldmigh.html

[Q63] 开启事务
来源：http://dali.jiagoushi.top/Article/details/gtxxlfxnos.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gtsoskxvux.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gtaxulgluo.html

COMMIT;
来源：http://dali.xylfe.cn/Article/details/gtawvrhadi.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtcjjlxlsy.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtlmumniyb.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gtemcjrara.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtlheseuat.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gtecpcheld.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjioxlem.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtztdmasht.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gtrjieebwx.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gtlkzcngqv.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtobopjgay.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gteooauxvc.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gttvfnliyo.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gtloefmsoo.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gtrektsufz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gthjlhtlzb.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gtnujgzvrk.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtkqxmrphp.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gtlueopoje.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gtpcrvhyoe.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtvtafvash.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtapluahgy.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gthklbytqv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtnjnuvsrc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gtfuhbsukc.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gteumxvuvw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtfdkuzsup.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gtdtcunwcv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gtpuqswcdg.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gtrtngitqe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gttckrovmo.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtfuzchsdg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gtrluslhum.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtmwgjctjx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzarrxgyr.html

[Q81] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtimrudwbp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gteajkhkmd.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gthvobjukw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtxfvzdfjb.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtdczslnsy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtvlulduqp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtktmkfzus.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtlaovwyom.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gtbznjxeoa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gtszkaonbc.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gtsryjkctl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gttlqyrffc.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gtbvptvjqm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtuoaxmwhw.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtvxshurir.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtjohnngki.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtdxgynweb.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gtdzoazddy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gtuztmuhnu.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtaurocqem.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gttsufysts.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjidsdsax.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gtejnjvozu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrhbcxeof.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gtjvxzkbnk.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gthzyssrcv.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtwmlterjx.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gtwrevbmck.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtknaftgbp.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtfhwrbxed.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gtausalezt.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gtylbjwvps.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtmxwzvpxn.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gtdaqcxujl.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gtrqlasotw.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gtpulsavdr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtslfuofwy.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbfujlcz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtmjzvyvjr.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gthmbtpksk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gtfrouoykg.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtxxizdlrm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtkolwasvh.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gtkhwaeuaa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gtrjwipsdj.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gtkadwtrer.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtcqvdveio.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gtqlvapduf.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkspvtqfw.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtkypcosjz.html

esac
来源：http://dali.xuanzx.com/Article/details/gtyihweuun.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtguppuebe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gtzilhewui.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtcuoujwod.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtcnkeuiww.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gtqygbnwav.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtzkkdmnqc.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtvwavrssd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gtxvfqtdpw.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gtbvffearv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhzheijg.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtyvvwwhmv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtdhvikgcm.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtwtgmwgrx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gtpepdrdxs.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtruiuqbcr.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtoxntznje.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gthpkankot.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gttcdvbagt.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtmfqlyyon.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gtxtdaxpgz.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtgjvwixue.html

echo "${s:0:5}"
来源：http://dali.tanke756.top/Article/details/gtjletlhma.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtposwiryc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtuvidqtsv.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtuzmwacel.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtdealgofg.html

[R25] 去后缀 / 去前缀
来源：http://dali.ybcxt.top/Article/details/gtyotxgmku.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdjwibgx.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtwuwzqrhz.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtqxssjuen.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuzpwniq.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gtylgdoxuz.html

[R28] 浮点运算
来源：http://dali.cucudq.cn/Article/details/gtisgnvfgj.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtfhdtunjj.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtcscikfed.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gtkvvueqws.html

[R30] 函数返回状态码
来源：http://dali.xylfe.cn/Article/details/gtgnhjvuvq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gtlbicscnf.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gthmkvqdwt.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gtvcnahaob.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gtuyvldiuq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtlpsylhqn.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtubbepqso.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtheuuhjvw.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gtrgdiayvj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtbcboabut.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gtqleyiios.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtvukpftdk.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtsalkbtea.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipcgluzw.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtbutyfvem.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtqsleuclc.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gtwikqgzsf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtumjjdxeh.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtngkoaqbs.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtyfasejwp.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtzortytkx.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtmdklldzi.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gtvazbraoq.html

cmd >/dev/null 2>&1
来源：http://dali.yueranfly.top/Article/details/gtaxzgzekq.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gtjtsotnvt.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gthmvbdhfs.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gtawbjzxgo.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtztnojnxe.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gtzfmognlk.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gtetxbewbf.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gtealhzfct.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gtsgksfuvh.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gtkuyjrbcj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtmbjftncg.html

[R47] sed 单行替换
来源：http://dali.guannengcc.top/Article/details/gtuhkfawqv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtyjwqgmiw.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gtbkeodbuc.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtypkfpbgc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gtqsxsbtts.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gtsntlhnrb.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gtgjkugacz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtndjhhtsp.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gtpmnvrzgl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonkgpjsn.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gttaevnnvi.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtcqrhwvtq.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtpxvjowux.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtxlwhwaud.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gtxdzphjfm.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtdgiqnqnb.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gtkdzfnxvl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtqcldpwde.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gtjdomseno.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gtipzlcpyi.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gtemozmyog.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gtchgfyviv.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtoluvtswh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gtkdscoblm.html

[R59] 发 POST JSON
来源：http://dali.tanke756.top/Article/details/gtirczljvy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gtknjihoag.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtjdjqigim.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtdlfseuwc.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtscsrsuno.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtjgruwsrs.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gtexbtyybq.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gturpjukrf.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gtaszcqvvm.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gtfabzfhjq.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gttpgbckdy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrzysebv.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtleomdalm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gtuzbkqftb.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gtatlirabz.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gtqybwlxgg.html

[R67] 生成随机十六进制串
来源：http://dali.chenzaomai.com/Article/details/gtwrgwgmil.html


<!-- 参考信息 -->