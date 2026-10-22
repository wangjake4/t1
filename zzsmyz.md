代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnrxbzkc.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gt2uosssbbt.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2tmygvbvl.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gt2kyhpqkfw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gt2gmsfncwy.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gt2pbssymdd.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2afjfeqcl.html

[Q27] 条件计数
来源：http://dali.yueranfly.top/Article/details/gt2bukphtuk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wevfxeli.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gt2ztahdmmt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2kayuhuin.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gt2ysbxyotx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2dgufhtzt.html

[Q30] 分组统计
来源：http://dali.yanxiufei.cn/Article/details/gt2pwwphdjn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2zqdoxirg.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gt2vnoeyqcl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gt2uojkpxnv.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2kdomynjm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2gxtzbkbm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gt2wlfzfhai.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gt2xfnpqngm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.kuanghao11.cn/Article/details/gt2ueahsotf.html

[Q34] 每组取第一条
来源：http://dali.birdmap.top/Article/details/gt2mjbxzzmn.html

SELECT * FROM (
来源：http://dali.sufxvd.cn/Article/details/gt2nkxwxqsx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gt2ekfwjlyz.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gt2mqlvfohz.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gt2ixwagjzz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2bnvizqwo.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gt2cnxizsfo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2gzveuwsv.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gt2lmhmyjkz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gt2whmsvtlh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258888.top/Article/details/gt2qecwcfjw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gt2rnvlvbvz.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxtowhci.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gt2miizzqgj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gt2tilnkuwd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gt2kuifreig.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gt2hrokzepm.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gt2obxwbmzk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gt2xezrksxa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gt2ysdmtiao.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gt2erkxyort.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2kealcklz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gogol.net.cn/Article/details/gt2hncgsepu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2sohbmkco.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2abkvhfqx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gt2dgxlmyfc.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gt2mikcboor.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gt2bsvfsdvt.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rawvwjjm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlddjaza.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gt2vmzxrutb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gt2aqvpjpve.html

[Q47] 与平均值比较
来源：http://dali.aizwys.cn/Article/details/gt2xxdkxzyk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gt2xbusfobj.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gt2exdcxkll.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gt2alkyxtdz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gt2wocerqiq.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gt2yudfczjl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdzcmceo.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gt2ryxrbpkc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gt2dwbnvzct.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gt2mqwiajfa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2shjdxobo.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ueqadhui.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2obazjsqw.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gt2sxxrepyq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cashguo.top/Article/details/gt2jhgrscdc.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gt2gmxqdkhb.html

TRUNCATE TABLE logs;
来源：http://dali.shzxlz.cn/Article/details/gt2czysqhek.html

[Q55] 排名（并列占位）
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdmudpmi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gt2mgncdrhy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gt2zyjiqxzl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gt2vpljudjr.html

[Q57] 行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldbxayiw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2mmkieobr.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gt2slsvcnrn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2brgbiodp.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jupwowhp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2ukuoonyb.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gt2xdmjwhov.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvtxypzc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2cfqiqhtb.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gt2zjcmaqpf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2jucwkymz.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gt2jbuxbfej.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2estskueg.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gt2scxdwibd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubwpxxwo.html

[Q64] 提交事务
来源：http://dali.hammf.cn/Article/details/gt2rifkbdwj.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjsrlshz.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gt2tweqwzkj.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqujoazb.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gt2tlartrey.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gt2rerfywva.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gt2wslzztvw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gt2rctzefjj.html

[Q68] 保存点
来源：http://dali.gzhubu.top/Article/details/gt2shzoofft.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gt2tzpxwghx.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gt2stukydal.html

[Q69] 查看执行计划
来源：http://dali.zycfv.cn/Article/details/gt2kegyuowx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gt2bivrqtwr.html

[Q70] 更新统计信息
来源：http://dali.kuanghao11.cn/Article/details/gt2fpzsntxh.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gt2qzcusain.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gt2ypvdfxuk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gt2bgkbcrla.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gt2lvlfglnl.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2ibsquvim.html

[Q73] 查看表状态
来源：http://dali.jiagoushi.top/Article/details/gt2hhiqmjyj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gt2ksfjjkhu.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gt2nfgsyjmh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgufenzy.top/Article/details/gt2mexevkqg.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2prwlfaan.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2bgpskhts.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gt2szilsqkk.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gt2hmqfndan.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gt2shjjizjv.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gt2sexuqqww.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxuanxn.top/Article/details/gt2ckdxekbk.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gt2iszlrndn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gt2gjnhctks.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gt2mbqorjkc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gt2ffuunkoj.html

[Q80] 字符串截取
来源：http://dali.c1oappe.top/Article/details/gt2kogrnarp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2udvaxrny.html

[Q81] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmiilnuc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2ofggleyq.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gt2lvueahgb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2xurryvno.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2ktvopifu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2qibeajge.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gt2ojkwgizr.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2hxkaytde.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gt2cwrnuuow.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqilfjvn.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rghiyjbw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gt2tgbdawnv.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2daysnwjr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gt2rpodlvas.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghntqecm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gt2sbauxbjc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2qzkvumap.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2mgpkwajn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdhvjpxd.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gt2rigwsooa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258888.top/Article/details/gt2iheicotq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2dqyxuepj.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gt2susjklxo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2uwyfaidi.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gt2impbxnkf.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gt2qrqleoxo.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gt2slgcimjs.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gt2kgdsnveo.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gt2oyllqjab.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2okfethuy.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gt2rxieqsjm.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gt2oajffdce.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fzhhl.top/Article/details/gt2vzgpioxq.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2cidaqwcz.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gt2wsbexhim.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2ojebfxuv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2qgtcbktu.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gt2varloinn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zowqunsd.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gt2etpiwkfs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2jgijshfq.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2vcfbtikv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2qdqohsni.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gt2kbphkehy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gt2rpfmlbkb.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gt2boqhiccs.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gt2jiwfknyk.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gt2ylhffqsu.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gt2nxehfjwd.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrjprkts.html

esac
来源：http://dali.daria6918.cn/Article/details/gt2vmabqjze.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gt2qktvkjba.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2ngbbgkhw.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gt2zhefiuys.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gt2scvffxmd.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gt2kmqlmlbj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mghyngfb.html

[R15] while 逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2lmvvjqnh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gt2jnsszlua.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gt2asbadljt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gt2yabndiib.html

[R17] 数组定义与取值
来源：http://dali.c1oappe.top/Article/details/gt2cnubboob.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gt2mlaoepmz.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gt2pfrguspq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gt2slronbua.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2sxxoljqv.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrtggonz.html

[R20] 关联数组（字典）
来源：http://dali.yanxiufei.cn/Article/details/gt2ltnjylth.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2binpwgdf.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2falwaebi.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtikhydr.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2hrmjhbkc.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gt2evzxgwna.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2hiepflbj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2aeqzuabm.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gt2fevfhvro.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gt2eaozabnh.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2kalrjojm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gt2jvyjazts.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gt2vzunpsjr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gt2vujnrhty.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gt2vyorqhzs.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gt2uwqtdytw.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2tzbvaptj.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gt2jzhtofmp.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gt2rjvfmaqc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gt2vosrmrew.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gt2upbhusqa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gt2wvsnajdc.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2xodfndpe.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gt2tmjzoilj.html

[R32] 参数个数校验
来源：http://dali.gaohongyu789.top/Article/details/gt2wkitfqkt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fptpqsaz.html

[R33] 捕获错误并提示行号
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwkrqdme.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gt2soscuupj.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gt2lpasdhaa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2qkhubkgg.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gt2nusvgwzd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gt2pctqywtf.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2smxnquxu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gt2sdszhghr.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gt2lbkpfiub.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gt2imwzxmdu.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gt2nerbvtir.html

cat a.txt | grep -i error | wc -l
来源：http://dali.haohaochexian.top/Article/details/gt2sewrvkmp.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gt2iefpflil.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmaprocb.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gt2qhletjfk.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osynomkw.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gt2npxdmgnb.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gt2mxzymxpj.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gt2fhqfviyk.html

wc -l < a.txt
来源：http://dali.guannengcc.top/Article/details/gt2qwxzrkoy.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gt2doqodjaj.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gt2zqtsbpcx.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gt2kpcjqqgd.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2iataxstd.html

[R45] 批量删除
来源：http://dali.xuanzx.com/Article/details/gt2lfjgmefa.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gt2xnctohsv.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gt2whjyfnzp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gt2dfrenmnc.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gt2wpjomzxd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2bxsqftsn.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gt2dotdfuep.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2vefdqagc.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gt2vnvjnsbe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gt2wqipwbxs.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gt2kaknyixz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2adohrqkn.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gt2ssjnrwmj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gt2tcbpgsox.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gt2qhxlusdn.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2dlqmheyc.html

[R53] 查看文件头与实时尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfgurhrg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gt2kqgmprnw.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gt2zmjyddsi.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqprcxau.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gt2wjwwhanr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gt2evdjsdvi.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gt2ieppcdnl.html

scp file user@host:/path/
来源：http://dali.xziqi.cn/Article/details/gt2iqazmfks.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gt2metyighc.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gt2cmwhlvzu.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gt2olhsbbbx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gt2oququnfy.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2sunizrvf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gt2itkyllmr.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2sbbmjchu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gt2njulxmav.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gt2zrhoaujl.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gt2innjuqsd.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gt2arrcyvra.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gt2annjvury.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gt2ryczokir.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gt2atjyhlzi.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gt2yrjpuejv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gt2ulyejnfq.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gt2uwbjtxxg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gt2olyjcxiz.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gt2kmjnjzoe.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2eabcwpyp.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jydpoywf.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gt2bhvoawuk.html

[R68] 计算文件校验值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acahznph.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gt2rsliowqm.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gt2ayccnxir.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gt2vnihtdph.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gt2ceveipit.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gt2favkoxes.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2nzzuwrpk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gt2nyvuwpot.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gt2llvduzdg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2gauyvfgh.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gt2mcbhtoie.html


<!-- 参考信息 -->