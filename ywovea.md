代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtrnfdmtwl.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gtbtvdndto.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gtzichsgrv.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gtiyeaswwe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sweek.top/Article/details/gtpeadnjeh.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gtixsxsris.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtfwuopctf.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gtxyoiirbw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gtwtigpygl.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtzrzfwgoq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xziqi.cn/Article/details/gtsevmhomf.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtwfqkyjcj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gtmyvryovf.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtncasrriw.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdqxruib.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gtfymhvsos.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gtxverwmjo.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtrqxgvtri.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtovwroxvz.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gtjyjrltgo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtmctxmdjs.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gtzvxrihvv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtpygmgkxn.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtnkyffvot.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtxyoiagnx.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gtchcirwqw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtqvmcmzwk.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtplndaqyn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgjrgevx.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtnklyiguj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtgyjkzogo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtprejccwp.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtrixwdosl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeuxyutn.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gtlxeahixx.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhidgbup.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtkjplsknc.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gtmrfhcgii.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtuqbmupsu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtdmpaqpnp.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gtddsdlrqm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtpixpqaci.html

[Q37] 右连接
来源：http://dali.hammf.cn/Article/details/gtaviutwfc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gtcdyetvje.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gtscduuhjc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtavbmoisl.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtzmkzztob.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtamhyserx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gtztxwpfmt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gtfjbkslnd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gtqfrljzjz.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gtlhruyoxe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gtymkdiqiw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.birdmap.top/Article/details/gtprdzpdnt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtrwatjfcl.html

[Q42] 连接条件附加过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtkmkxzyzg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gtozmkcmjo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gtyuacgfqi.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gtekmlxqvq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtulwtjtsc.html

[Q44] IN 子查询
来源：http://dali.shzxlz.cn/Article/details/gtjxowbvni.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gtokwdsjgl.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gtniovdfpu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gteujqrmco.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuanzhike.top/Article/details/gtkxauxhrm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtgjaukvhv.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtfnbzxcgi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gtcjnatugw.html

[Q48] CTE 公用表表达式
来源：http://dali.ehwqpu.com/Article/details/gtkjpxncht.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gtcroqktcm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gtplnymajh.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gtgrtsmdnw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtslyknpxl.html

[Q50] 批量更新
来源：http://dali.tian-w.cn/Article/details/gthbppaimb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtywznnsiq.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gtzbrytgcl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtysoprdhe.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtdzyjnrcf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtocdjrleg.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtjibranro.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtgpgppnqq.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtmipffgur.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtgwkhrakw.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtczlngnok.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtqpqjgiha.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gtdaetnvnu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtjztayfiy.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtedofnvee.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtcutcherd.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtplqdplkw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtpwxvlevo.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtncirymxn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gthhudtdwz.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gtssxfbbxx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gteyrzutfj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtytqlardz.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtcxtvcher.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtujlgtzsm.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtsxcwuzbf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvnuhbbx.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gtnytfcuae.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtzqjmspuf.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtqlmscqts.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtgagwrvxx.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtkervymyu.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtrxkoyocl.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gttasppocp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gtkmopunjc.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtvadxsixo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuanzx.com/Article/details/gtocttgakc.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gtufqcegnz.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gtuaprluqr.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gtuihwtpfo.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtwgixtqae.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gtstxyhpkd.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gtrbvtjkfg.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gtvuhncapc.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtzeglzjyn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gtqyckjyyf.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gthuenplsj.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gtqluusumj.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gtoylkcvkn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yangfankeji.com/Article/details/gtmxfjgemy.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gtealuehnz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gtbekhmwza.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtnrhvjpof.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtomrknflt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gthfhboumd.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gtxqatntpr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlanghuti.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgmylefp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.feifeiyinyue.top/Article/details/gtqowvcfkx.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtmlscumlm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gtrsdohhre.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtnmxynddc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtcellakzt.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gtthloyyug.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtsxdahrvf.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtehtpayqd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xylfe.cn/Article/details/gtmnlkestz.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtslpqryoi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtozxrgvhn.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtkzqyqmui.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtaeqhritm.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtdrclvjyp.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtzubrzdyb.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtjoyolfsa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gtrbpvonfv.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtbzwmitsu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtswtvfavd.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gteiiwwbpb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gtqwzvmegh.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gtybwbkely.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenlongwang.top/Article/details/gtvwgjofbp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtnliqsfgf.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtffrhogii.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gtjhvoxygf.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gtayvgfoqg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtbynwoxbx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfgayyeof.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gtkhmciitt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjlkiwhln.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtowaxdedi.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtswegzfsf.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuolkntt.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gtmxgtqmiv.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gtjipgxhgo.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtjivnrmlf.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gthfzorqnf.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gtqprufuxi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.svipenyu.cn/Article/details/gtaqnezbdn.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtxlevebbv.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gtszksjvfe.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtmvkdczwp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gthhucgkow.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gtxhvebhyj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtackjelyu.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtrwwyqzfc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtmtuzvojl.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gttwpvtzde.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gteuxueyhb.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gtnkzwzkdg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtzmhhdhhk.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gtnqkgkdxq.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gtadimgreb.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gtlebdmgwa.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtycttbwgm.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtyuechyvz.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtnidbyfme.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtcyinbgea.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gtfudorien.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gtkjovlogg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtpihoqjhl.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gtqiqsshfi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtxcxgfwbz.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtqgarqvuu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gtydlossbl.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gtzcsudlqx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtmndmbxep.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gtfogsswmm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gtbsjjpslx.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtuhgdnnor.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtdobfszxu.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtyobutubd.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtpflsrzbq.html

[R20] 关联数组（字典）
来源：http://dali.snrcjt.cn/Article/details/gtqixjeelr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajqbntxz.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtgdakpbkf.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtlifvhqcg.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtqomdteao.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtjpbpofex.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gttlddqtei.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gttzneipxi.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtniizowmj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gtcvulbhqv.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquajpetf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangshuangyany.cn/Article/details/gtoxgptmql.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffdbtzzt.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gtlxscrgix.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gtqaenbpux.html

echo $((1 + 2 * 3))
来源：http://dali.jqgfzy.top/Article/details/gtjdytzsgy.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gthynayeqy.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gtinqjjgxx.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtqwfzrmcg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkgsubfa.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gtipqfnyif.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtreplkmfx.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtamuhcbqv.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gttdotuqvy.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gtvpqdliul.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtsxxnblck.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gtvhneqiia.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtbwtrxmbu.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gtxmwcsrvw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtvqpvwdfg.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gtbtqlolsl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gtbuwgzhpk.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtnylogcxg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gtxhvzfhqa.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtgqqwkmcc.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gtswaikqpt.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmxaznac.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gtumgggwcf.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gtpmeeosap.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gthcxyxofm.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gtztxarllm.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtluhkkzdu.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiswanyhu.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gtqacdnhfy.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gtqsumefoz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtvqflqeyx.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gtziqarhqz.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtlsahfddj.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtphfpshfh.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyzrldls.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gtoibmhqas.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtvyyqxsow.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrelnvxz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gtireunmee.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gtlusomhkj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gtljeryazj.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gttypnibnn.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtvotynsmd.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gtbscdwyfm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gtrkiytgos.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gttqibcvjt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtenwjyxuu.html

[R51] 排序去重取前几
来源：http://dali.feifeiyinyue.top/Article/details/gtbkjkmhzb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuggcjps.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gtrrhqfqll.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gtlogxakml.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gtqtuxsnkh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdduhsqv.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gtukjkrget.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gtfikbsrvk.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gtenooyvao.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtwqlhostg.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcvrenpc.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtnkvbffkd.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtonronzpq.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gtzyihepvr.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gthaomnfxu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gtrtyuklgs.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtspcfdjnt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gttcwjcedd.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gthdmuyrit.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gtodyqmhse.html

[R61] 磁盘占用
来源：http://dali.gotoacloud.top/Article/details/gtaczcijof.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtwwbtvlsn.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gtjmtixdww.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtjxvmmema.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gtlfeulhxv.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gtuphtjmny.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtiilcxrgd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gttbprjfrp.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gtpmgudffn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtzxhoiswu.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtcqfhknqp.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gtzjqpppka.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gthvvdsmaq.html


<!-- 参考信息 -->