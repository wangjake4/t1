代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gt2zuxelwhn.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gt2vjoeftiz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gt2bqipohzz.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gt2zrzjkjey.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gt2mfdvgtxp.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npkfjkdp.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2ramwsltd.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gt2soczycni.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gt2kzxjdwak.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gt2djzibplr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhunjtyv.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gt2bvujagpu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqhkzutw.html

[Q28] 求和与平均
来源：http://dali.sufxvd.cn/Article/details/gt2inzcvstb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2zbzcztjf.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gt2emjmlqtb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2hhnhamog.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gt2rlnbwgvb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwhesejx.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khbrusyw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gt2fvcanziv.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2esujucvz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2uiynxzmq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gt2tkmcrtss.html

[Q33] 多列分组
来源：http://dali.dashuyun.cn/Article/details/gt2zxpixgck.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cucudq.cn/Article/details/gt2xffvyukl.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tiynmbsf.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gt2fjvdwxhc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gt2sqkfpelc.html

) t WHERE rn = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2goydvetn.html

[Q35] 内连接
来源：http://dali.snrcjt.cn/Article/details/gt2btutowvm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gt2nxobespc.html

[Q36] 左连接
来源：http://dali.c1oappe.top/Article/details/gt2kbdliwxr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gt2nahlvysf.html

[Q37] 右连接
来源：http://dali.xuanzx.com/Article/details/gt2fotygsns.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ppjwa.cn/Article/details/gt2ajclfrgm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmaispum.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gt2zfbkcrij.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gt2brostyiq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gt2hcojniyd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258888.top/Article/details/gt2otpghrcb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gt2rcyxrcig.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gt2zvukbheu.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gt2pxxwiblh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gt2nhpvhsir.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gt2isrrvftk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gt2dsvechjd.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gt2vvmpoqnt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gt2lemerdrn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gt2igniqrvz.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gt2abmdkxyk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gt2geaeshrv.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gt2rzjtjhmz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenjidiqi.icu/Article/details/gt2trzlumxv.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gt2yytajqhy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gt2hllkgbib.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.0kj1m.cn/Article/details/gt2mhbecune.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2opsrlakt.html

[Q47] 与平均值比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdsxnimo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aibaodan.cn/Article/details/gt2jadtjiea.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gt2cwnlkwyg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gt2cyqiwvsv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2kdazneca.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfmoeitk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2ztnvlyqh.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hohblkgy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gt2ksyhazen.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gt2qbokpttd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2kufaapat.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gt2sqajyhya.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2zwapukrs.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gt2gkalvrrv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gt2evcalypo.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gt2cefjppeo.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blvqemob.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2bxivrkhp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2ecphzuwd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gt2npewqcgn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2qdcfjytd.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gt2iuaayyxu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2ayjkeszx.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gt2rcuymneg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2oxsifbxn.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gt2ajhihezg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2lowzbmos.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhekbppv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxuanxn.top/Article/details/gt2ayvjmbiy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2qpkcxvzo.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gt2jwjvadcu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2zroxlymq.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwdioxlv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2gfzqhujn.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gt2uhgxcnex.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gt2anparvop.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gt2tismcind.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gt2unchrnhg.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gt2afyfqtnd.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gt2tkxqmvic.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvlfcifd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gt2pumkifpy.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gt2nfqniurg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gt2qiemsdxi.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gt2bwxwjfwl.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gt2mlhftqsd.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gt2pnempred.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gt2qtkqtuve.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gt2ptebrwxt.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osvktntv.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gt2qfgprxzz.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gt2ubxieafa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gt2ypxpibcz.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtulzyay.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2edduoadq.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gt2mshkotpy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2uejgppxn.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gt2suiiqdgr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gt2uvfwxhwg.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2jmqkbxjo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2snpasxgk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gt2khoyltai.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mahlirmy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2vsvjeogc.html

[Q77] 时间加减
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zelhlill.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gt2wuykobgu.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2xzaewgyf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gt2sstpzlhw.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gt2aatkkyag.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gt2lrunxvjx.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gt2jxwppdzg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2rrcelebw.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gt2tbymokjz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2ncubdfek.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmffxnpl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2zufanfip.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gt2fxujmljb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2gjjekpnr.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnilpzvo.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2efwsfydk.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gt2avyxgwnq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gt2jspproya.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gt2ipsncsit.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gt2vxeeppmp.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gt2hjyjjsoi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gt2fexkzclt.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gt2kukgkrnv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gt2fembgbyr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2afokckks.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gt2cbpydvqe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2frhyspma.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gt2pycymjzs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vaajvgtp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ctmzjglr.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gt2yohlcxfx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2bjknthvy.html

[R01] shebang 与严格模式
来源：http://dali.sxryk.cn/Article/details/gt2mppxsmar.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gt2ausmpvvy.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gt2olyvgznr.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gt2xcgljdaw.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gt2eqqvzold.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gt2ciwjvotc.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2zymtsiam.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gt2chiltidu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbouodwc.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gt2imwpdayb.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gt2pfwrmznd.html

[R06] 判断命令是否存在
来源：http://dali.jqgufenzy.top/Article/details/gt2bbeonipl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2toaizxrv.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gt2ttcfyzfp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gt2yywaupps.html

[R08] 数值比较
来源：http://dali.vqdsnc.cn/Article/details/gt2kurrzahl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2emkwqfzk.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2qugzvied.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gt2ipnsslfu.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gt2ymiriowb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gt2gxvxpkep.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gt2fsmrcxpk.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gt2xbbwdrqv.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2wklgfcun.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gt2pwvjfphg.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gt2cixeluaa.html

esac
来源：http://dali.tian-w.cn/Article/details/gt2iilhoyai.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gt2pwsgcgzs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gt2qmliecho.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2kaxouqlk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2mhsmmcvr.html

[R14] C 风格 for
来源：http://dali.gzhubu.top/Article/details/gt2leggcssi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gt2nenncnsm.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtswdwfu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gt2enttrmiy.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gt2yzjtnbmp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2hfjctgcx.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gt2eatzlisy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gt2cjtwtcik.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gt2lcebkdqn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gt2zgparxza.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2tewlkotg.html

echo "${#arr[@]}"
来源：http://dali.mhx1999.top/Article/details/gt2odnjxlya.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gt2iiiinkfu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2lvxepaku.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2pirjwhwg.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gt2zkiqpwig.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2fzcplwmn.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gt2ewmcurep.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gt2ozpyzdqd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gt2jpeofkzq.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2rovvcfcp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gt2kxsrnfat.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gt2spvonenk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gt2xqtrwvfb.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gt2qfustwiz.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gt2uamkxquy.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gt2cprgebwq.html

echo $((1 + 2 * 3))
来源：http://dali.gogol.net.cn/Article/details/gt2dlovunln.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gt2bphxwadf.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gt2inwaaxyo.html

[R29] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gt2vtjzqrno.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2knghacfg.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gt2yojtwawt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyxajjde.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2lsmessnt.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gt2xlakgybs.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gt2kuzenvko.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2utstbhem.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2klruiich.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gt2iibbatqg.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gt2zaxkelix.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2ongfhlno.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gt2hhfaakmo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gt2cxckcssk.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gt2uahlcewv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gt2nldifpdx.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gt2jjyrmsot.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gt2xdgqvjjn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxseeeg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gt2aemwjlxt.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gt2fyirxous.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gt2lznttvin.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gt2cqqmikqf.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gt2yvyhuwis.html

[R41] 丢弃输出
来源：http://dali.nwbrower.top/Article/details/gt2ntlufbwg.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gt2dbkouaua.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gt2vzjhaigr.html

wc -l < a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2dpwctjgz.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gt2rgkpbjrq.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exreviah.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gt2zkgowiqn.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gt2cqcnvtfd.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gt2fmgcrsfr.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gt2drysaysz.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gt2phqtkvft.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhejrhip.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gt2ruvnqhot.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvfugmv.html

[R48] awk 取指定列
来源：http://dali.jqgfzy.top/Article/details/gt2fgwubwoi.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2drfoeegx.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gt2dbfbczwe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gt2xzvezcfu.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gt2pbgjnszs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmexjulq.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gt2arlouhln.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gt2zoovgcmz.html

[R52] 统计行数
来源：http://dali.snrcjt.cn/Article/details/gt2hapnrhkp.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gt2hgpmgqvr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luybzqqn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lsmxgmeo.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkmaggmq.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gt2eebutxkw.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gt2dozoiumc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnqzz.top/Article/details/gt2tpvqoklm.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gt2glxrkgyv.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gt2zrsgxjmg.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gt2upeeiwya.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gt2qaurvlff.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gt2sggjlxyj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gt2zwvmcktv.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2aswxhjex.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gt2fntsuhee.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2gjercaih.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gt2bhxttmed.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gt2kpwgvopu.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gt2dwhtkoaz.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gt2lrkqgrdy.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gt2ldtvknzi.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gt2eebqnsvf.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gt2qnvzawjo.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gt2hzpyijkp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gt2kuraqnac.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gt2aydnporm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gt2anclbhci.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gt2imhxngnh.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gt2szkjbafn.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gt2sphojhxc.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gt2wnaqvzbj.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gt2gkwmyqgk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2kypvvmeh.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gt2ycshswyo.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpljvmhj.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gt2ruaanydj.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gt2gfuuilnx.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2qrgecphz.html


<!-- 参考信息 -->