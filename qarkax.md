代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gtbcncdtwp.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gtajrceanm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gtxrlmkcmj.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gtfxmsuyhk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddifbxht.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtoqzoxqgt.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtzacteuta.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtylufpyrw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtidwgujfb.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gthsrtzrno.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtkvjeqcic.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gtygwxxijf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtsaspxxll.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gthhjvasgw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gttwmdyiqs.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gtcdnnfrnu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gtgzjyersn.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvhmqdan.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtawaffoza.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gtotpxbcez.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtifxnfzcc.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gthmcfkfdm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtmselfwno.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gtjhnyawcj.html

[Q33] 多列分组
来源：http://dali.hywenlv.cn/Article/details/gtnnthhsqp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtijbddiml.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtrxrghnfg.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gttbmbypld.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangdashe.top/Article/details/gtknlwqike.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gtfoxbgqer.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtczjplqug.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gteatckdeo.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtuyhfijos.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtfwuctipi.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtufmvrkvp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtwdsvhdld.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hywenlv.cn/Article/details/gtodlujunx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gtvwodfgoc.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gtufvnzxlq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdxascdd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gtdnhcxgjl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgkahcsi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwpgsmar.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtefvrzzgw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gtadkfcxlh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyculwqk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gtdmqeqfvt.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gtcfpcnzgq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtkkzngccp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtkihcjvqa.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gtmvtyjecy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuanzx.com/Article/details/gtoyusrkzl.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gtevmpbytn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gtazfimidj.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtkrhlnklh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtdxtizmvf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gtwzaxqrsi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtoyjkcwjh.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gtqykzfenx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtcuusnidd.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtqgacibcr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmasmvia.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtvdcbtdvv.html

[Q49] 更新单行
来源：http://dali.quarkkingdee.top/Article/details/gthvdbkiru.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtsutzihyh.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gtxepzocnh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtgvmeylba.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtygqtplfg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tian-w.cn/Article/details/gttbihcoso.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtfczdtksn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtaqovqfbu.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gtmqxqnsoz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtiqwfuajk.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gtrmarhkbx.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtifunnfgl.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtlztgihkh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtksoylizb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtoavnbfwt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtlcsxvcya.html

[Q57] 行号
来源：http://dali.yuanzhike.top/Article/details/gtveettkvj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtikprbmin.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtfuttcyuz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gthmnxwsep.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gtaxflgvqz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtcvhtekvc.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gtgtatwxpv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gtsbzyfmao.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtqelaphgc.html

[Q61] 移动平均
来源：http://dali.cdnleiting.top/Article/details/gtpvxxwlyq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtvngmegtt.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtssvlntse.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtqptyhzci.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtceetbscc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gthogbgimy.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gtnvujakcb.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtpuxhfgyh.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtlbribrey.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gtmqpuksyl.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gtmysybpeh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gtipvsaigd.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtqaqgncio.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gtzalvzhgv.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtnbwxxtci.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtpqzeqdmv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtpyurzdzb.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gtrnwiizak.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gtgocthiuc.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gtaecjkscy.html

ANALYZE TABLE users;
来源：http://dali.quarkkingdee.top/Article/details/gtuhiowchh.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gtqurtlchd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gtyvssxtbs.html

[Q72] 查看索引
来源：http://dali.yvedp.cn/Article/details/gtpximybzv.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtownzcsej.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gtikqxfsnt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtrdbbgwrr.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gtdffplgvb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gtfphvtyxa.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtpqqpzsdp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gteespavkb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtzogtlnyn.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtwmtbuwov.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gtptbkwjxz.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gtuxujqnce.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gtrhohcxzn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtyvzxelff.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.andypj.xyz/Article/details/gtymsxfwne.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gtfrmbaunn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cqqwz.cn/Article/details/gtztgmsupq.html

[Q80] 字符串截取
来源：http://dali.shangyingyoupin.top/Article/details/gtnsuwchyn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtjhwnjegi.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtcplagjch.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtvuhfomfp.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gtozatyvkh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtradcmygo.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtjgrbcrcb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtjjjlmusd.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gtizpxizkh.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtbuievmri.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gtnrixmkhi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gtoxzmuymu.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gtjfymrdpw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtdaceysoy.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gtqhqnzolm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgufenzy.top/Article/details/gtynbivuku.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gtaeonjtas.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrwynhmd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtdzauxifp.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gtcbjskssr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtchbslcfm.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgrsvvqo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtrtorammx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmyxittff.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gtcijdlfte.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtwqqnwtpr.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtovhqvhbv.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gtojpqiuwk.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gtgdzexlxw.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gtamtjlzja.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gtirchciga.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gttflknsow.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gtfrhfpzon.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gtuprkhqqw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gteidartye.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtsaqforuf.html

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gtunubibjw.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gtdrvtvkwi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtbxjstevl.html

[R07] if 判断文件
来源：http://dali.daxiang520.top/Article/details/gttnqsnodu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtbhxtvttc.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtjojjvtwc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwrnhbyx.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcshopxrc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtopfnygqr.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtricwtcqk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtsoebyjzo.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtwdlbjzxv.html

case "$1" in
来源：http://dali.hnxiangtu.top/Article/details/gtpkkprrsx.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmetohnf.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gtyvcxqccz.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgupikhmr.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gtiawalujz.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gtunghieec.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gtkcbcxwjw.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtgqacahgy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtjjihwbfh.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtzgathojw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtpruzlocz.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtzakrjptc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtdxocyxej.html

[R16] until 等待条件
来源：http://dali.yvedp.cn/Article/details/gtrbzhhaod.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtxdzelxbh.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gtqctmdhci.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gtzoojnfoo.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtdfrmlgzz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gtallsewrz.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtzytqicqb.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gtahwwznbm.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtiqrwhgnn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtdzjlosub.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtlhrjyiip.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gtjuhwrirq.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtqkdnkkeb.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtyxnxojnk.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtcfcxqphc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtolajrviz.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gthzqpsmgu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtoynyrpzm.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gtoblyhuff.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gtqyntyyoq.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gtnyugussh.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gtyjgqjmxc.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gttqnxvxze.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjiucexp.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtpfmcfcte.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtiobdaepy.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtsqxfmouu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtftfdmxhs.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gtkyvlwkth.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtnliwmabm.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtkgxywjyj.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gtkykpzhed.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gtwvbqepdr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtjgklyimw.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gtkrvighjp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dianchejie.cn/Article/details/gtqrjxftil.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gteyyqzwkn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfaucwbf.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gticcjaufv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtswqdkhsf.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtbhalgbyg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gtzsihjmta.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtwcyvnjsd.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtprwsaohg.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzlgimmb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gtilsbrbxl.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gtgvdxgpsg.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtvdapdito.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtjhuoxhke.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gtbkovesua.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtocijgzxi.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivctkakw.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gtljlrumwm.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gtelyjrmba.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiscnsnxu.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtoetiqohu.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gtkzrwmhpo.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtezmdleim.html

[R45] 批量删除
来源：http://dali.hammf.cn/Article/details/gtufjtpxws.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtqqwtkbwa.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gtgzjoohlz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gtrqeatpry.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gttlisvywt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtkhpjuprg.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtzccuywvm.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtdauoozwc.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gtpncvqznf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gtcohuuxhw.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gtpiskblah.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtwsnrotwa.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gtxojeucak.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gtwydlixok.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtdbyzwsrr.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gtzguzoqoa.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtbpryhubi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gtknkktmww.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtfvjvfvmh.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gtgsbdxyru.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gtnzimhwee.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gthszmrwrw.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gtdnckypha.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gtrqlxjptr.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gtbfwqfwwz.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtejyaffiq.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsgnhfhh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gtspxvxaoy.html

[R59] 发 POST JSON
来源：http://dali.tanke756.top/Article/details/gtcdmjrblz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gtnlxwzhrg.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtgwrygyzb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtmexpnybz.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gtseknbxnf.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gtjmhawigd.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtlzobakvu.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gtjxcnnngg.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gtyjvxsdti.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtxvodyntq.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gtevazpxxg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gthokliyms.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtpvyfmlll.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gtckcddoex.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gtrsidbrlw.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gtexruggdm.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gtzcvvjszv.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtnahipypb.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtxnerrcws.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfsluswe.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtlqpatfay.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gtlsrtkicu.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gtgkoyucip.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzzjtlgb.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtyxfbugbd.html


<!-- 参考信息 -->