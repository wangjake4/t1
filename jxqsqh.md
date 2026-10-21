代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gtwaoouggx.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtacbfynac.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gtqvesiilp.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtsqbzljix.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gtobdwnnzm.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gtesvfbdjv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtlhvlrkos.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gtnjlfezaz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gtekgzdgls.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtrlsocluw.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtlpbpuxzj.html

[Q25] 只取前 N 条
来源：http://dali.guowangkeji.top/Article/details/gtscpfxlwr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gtapqfzfzv.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gtszncfsbx.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtzesnmfzk.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtdkuyfcwg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gthqegnldh.html

[Q28] 求和与平均
来源：http://dali.chenzaomai.com/Article/details/gtggpckqjo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtetmusdui.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtqcbzafyu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnbbqjfei.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gtyemyawsv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtgnhlfnvv.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gtnohddrgn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gteauzblxr.html

[Q32] 分组拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtoqtdxwfp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtyryukgjk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gtehsrcmqx.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtozhpvjag.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gtghgdkwpw.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtlvvvgikd.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtdgvomrzz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gttjffosbe.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gtrrnmqnhr.html

[Q35] 内连接
来源：http://dali.yuxming.cn/Article/details/gtgxnkvwiy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtzqkmikbl.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtkvqnxlsw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtjtznzjgn.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gttzfkgxey.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtkfoyivub.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtsfdkmwfo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gtdwaazsrq.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvnjxnnt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.bjfxy.top/Article/details/gtomykttso.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigufen.top/Article/details/gtasulalox.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtjgggzpll.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gtsyqzfzbr.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gtmoeefkty.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gtkrnnokmt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gtjplihkjc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtdyelnmzv.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gthtolbzio.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtprstjheb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gtyhjtmxro.html

[Q43] 标量子查询
来源：http://dali.nanxinkj.top/Article/details/gtoopwhovu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gtrrkphuwo.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gtfarjqnxo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtkgyvifdc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gtwjfeaiaa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gthmdfdydk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gtybggifyy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtcqmelsdq.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gtqifqcenc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigufen.top/Article/details/gtepbdpfmf.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gtjamiycim.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtflagrkeg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtywkjgmtw.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbkcybry.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtonavckzp.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtfsiwnxwe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gtqgptlvcv.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gttftsznfo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbytkofb.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxibvnbqv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gtkrmxokbs.html

[Q53] 按条件删除
来源：http://dali.jianghu66.top/Article/details/gtvmthzfin.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtwdlfnxwj.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gtddmqzmvk.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gtlezaokka.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gtbrmzgohg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtwyzjrveo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gtavrcznzj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sweek.top/Article/details/gtccsntssk.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtxholnefe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gtcaiuglur.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtibcpolom.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtvgxhmxrm.html

[Q59] 分组内累计
来源：http://dali.pycfn.com/Article/details/gtamfvxamt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtwwiurmcv.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gtemqdccqn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gtdpdrsuab.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtqfxklguo.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gtvarjaxcz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtgyasvmes.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtvlqjoxmr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtuoygupns.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gtgklzxyxb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gttqtsagdl.html

[Q64] 提交事务
来源：http://dali.wangdashe.top/Article/details/gtwidyocym.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtbtxqmbvq.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtzjuacvnx.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gtaoudvtiw.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gtfeeiwcmp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gtqaufaylj.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gttufckkoi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gtgspxsenm.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gtefrektdz.html

SAVEPOINT sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtyeezkvaz.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gtuxmsfrzw.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gtbteuswzb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gtnarupows.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gtfibnxzdq.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gtxartilwv.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gtxfxsjvqh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangdashe.top/Article/details/gtpbefobzx.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtwjkpqjiq.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtwjuolwau.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gtixbqined.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gtjxlitjxk.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gtfrmxvohw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gtvxxgljmb.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtdlmvqzio.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtgtefhfbk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrpdezjb.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtdeabexhb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gtnhckwfmc.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtvbjqjpve.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gtkrhszzxm.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gtrtuwvzyo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gtsrhxcbjr.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtiivkmcmj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gtbahkradp.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gtimbbiqgb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmvogacx.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtsuyxoqzd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gthhylrbxx.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gthvlbbsoy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtozvhleub.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtnhnigxxo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtdpbivksy.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzliehnd.html

SELECT TRIM(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtxrytihmg.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtemywngtk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gthhsihyln.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtjbpokwlb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtrtdbxvcf.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtkcfxoxxy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiezkxor.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtoyeedhcy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtkzwzcbqw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtggcfhkyj.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gtdgyhbkuv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtjoshipvb.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gtevwgbdrp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gtvklxqyfz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtlpsyxgmt.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtkfnkjpdm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacgsdqch.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtwdourcdq.html

#!/usr/bin/env bash
来源：http://dali.sxryk.cn/Article/details/gtlmqgvxra.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gtieebenni.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gtnsqtobed.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gtzldkgjba.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtmcbsangm.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gtdoqynyhj.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtqmyixmxw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoygljxw.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtqfcaxodd.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtzyzxxebm.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gtmwahecwf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtnzssjwak.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gtewhbykev.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gtrnpckrdi.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxscihql.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gtygfqtiuf.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtbnxudymk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtgwcciaep.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtimgogjed.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtzifkpjub.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gtybnwbuoz.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gtrxewmqqi.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtcughdfpe.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gtkpbdxrvb.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtxizralzd.html

esac
来源：http://dali.9152youxi.cn/Article/details/gtoreebkci.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtvwasscyy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtteksbncz.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gtxpfmjkfv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gthsdrrnbh.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtosavacjp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gthdxhmlsn.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtnnzhwgrb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtazuyyqdk.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvqizbmp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbprmmxv.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gtnstinisn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gtlvjbjsrt.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gtwvqzgqok.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gthvovpclw.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzgbunab.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtofzhfnrx.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gtorxxurqp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gtfyhqrbpk.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtloeekuoh.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gtqtwwwkrr.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtcczqmnuc.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtfrqkaano.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtztiyogce.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtbzmffxhw.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtwrvudjab.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtgbmbqylo.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtofluncpp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtsonpgqij.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gthtotcmxi.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtgjkgvjcj.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gtvomnsvkg.html

echo $((1 + 2 * 3))
来源：http://dali.hysaishi.cn/Article/details/gtpqbfrqsh.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gtngoctixw.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gtrlpnvkis.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtlfhrdyos.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gtrokmgndz.html

[R30] 函数返回状态码
来源：http://dali.xylfe.cn/Article/details/gtjjfxzkfx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtvxpikwls.html

[R31] 局部变量
来源：http://dali.jianghu66.top/Article/details/gtfbwnhdnv.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtlvaxzjnt.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gtwukgurar.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzasaayes.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gtrtaigecp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tianlin.xyz/Article/details/gthlorvarx.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gtuompcgvx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtdjfsbmpu.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtvugjdjzx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtxyjgshld.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gtaetafiyk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gtpbirfqmj.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gtycznthtm.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gtyiaswpth.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gthqdsgsju.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gtkspwichp.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtrjttmzod.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtmdvuqidl.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gtikibqqll.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtpxsjlrbp.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gtgzipaaaj.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gtzfbmxxpw.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtoreptkkb.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtrorybjiy.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gtzjnhfxmf.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtttxebtzg.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gtznroqckc.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtfvuzwxct.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtjonenvtt.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtwiwlanww.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtkcrynmex.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gtufdwcubh.html

[R47] sed 单行替换
来源：http://dali.feifeiyinyue.top/Article/details/gtbvriaxsk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gtaiwzurrx.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtgyjdwnmg.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gtoieuztgp.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gtoqsxkflp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtaauwmoyt.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gtjjcdmhxb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtevbozpha.html

[R51] 排序去重取前几
来源：http://dali.yj20258888.top/Article/details/gtgseqdfne.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gtceiwqork.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtwfvqcske.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gtcmkslboe.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtfixwabgv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtpbnzmprk.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtezeegxmg.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtpiqheumk.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gtogmwlblq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtdmeupdgw.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gtgdksvtwy.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gtalscqbgk.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtpoigjiho.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gtjjfrpzku.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtzlbbhyug.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gtpfnicumg.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtcfwrdaju.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gtxrkmjzmt.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtwnwypsde.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtvdegyieu.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gtfwpvvybf.html

df -h;  du -sh *
来源：http://dali.jianghu66.top/Article/details/gtizpqyfoe.html

[R62] 找最占空间的文件
来源：http://dali.xuetiantiany.cn/Article/details/gtsnifejga.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gthquclqew.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtxphjfuoo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtyoyrhvqi.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmdqonfp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gtrlsqfsri.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtzyilxuic.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gtpsnefrwg.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gtrmmfawim.html

crontab -e;  crontab -l
来源：http://dali.guannengcc.top/Article/details/gtygoozdzv.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtuzkojbwf.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gtlqtewyzk.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtcjtunxcb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtynkwityc.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gthggkijrm.html


<!-- 参考信息 -->