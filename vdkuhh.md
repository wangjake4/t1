代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gthiaogiaz.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtstnmwfpn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gtcflzsiyz.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gtshrecgew.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gtyaqkzatj.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtnujhwkan.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtjvvsym.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gtmwsslkoh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwfrfgai.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gtykgpfkiw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtlzsoeads.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gtlefdrbwf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gtqokqoqwb.html

[Q24] 去重
来源：http://dali.0kj1m.cn/Article/details/gtcvwuoxfx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtctyfjcwv.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gtjtqoqort.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gtdwrlstso.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtmmvwgatj.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtfndjqhoj.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gttuvkmwpm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gttvnbnlfz.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtxoflppfc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtjfimrerf.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gthyehoaxi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtecymoqqc.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtiiqjgdmz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtjobjlppd.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gtwcshhhvq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtkohxliva.html

[Q32] 分组拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtvescmyjn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtxxkljqqq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrjzuxsh.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gtwnflouyv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gtvjjqyzvm.html

[Q34] 每组取第一条
来源：http://dali.hongshengwenyu.top/Article/details/gtjizsmhjd.html

SELECT * FROM (
来源：http://dali.zhoulong.xyz/Article/details/gtenmnevsz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtodefqpta.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gtgsbvpcof.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gtrvjwcfpv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gthyevxtlp.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gtpznnyexv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtekruxtxf.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtfrzcgkvb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gttbexfxkr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtbdnafnzo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtitakowlz.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gtakrneawe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gtrzlgwwle.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hfpthk.cn/Article/details/gtqoidyags.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gtimrdskcs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gtuqwdqzzd.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtjeuqaxdf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gtdxelxcer.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gtwssjybbo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtxrvbfkrv.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtdzzfkecx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtjqhwpphd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtdoakzypw.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkqxshdw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gtwqflunit.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gtgoxzzxar.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dianchejie.cn/Article/details/gtszyrksed.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtpjvcqftq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtscfwnyqo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gtupgdifhv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtknrhtadp.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gteemfcbux.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtgarpwclf.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtuuckobwk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gtgivxvnwm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gtqawsvmoc.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gtirjuicvb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtmibhqcvk.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtqpsmxwox.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gtqpzoaqup.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gtsrpwnqji.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gtrhveykvm.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gtgwrpieih.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtnjqhalki.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtobfpzyfb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtsnhghtey.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtuicehsxa.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtktmnccvv.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtfcfohzas.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gttxhirtsl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gtylrpnbja.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtaskddhhi.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gtwvlzrrrh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gtqydltzds.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gtlanbanxg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtqbumnygk.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmowyzdb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtamyemmlx.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gtaplzowdc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gtbhsujjqp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtajtmznof.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gtyghaerzl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtkzuwhxkk.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtyjyarqib.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtxkjcuozr.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gtikckavjj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtfvawfjst.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtjispcmxs.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtveaqgicz.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gthnyuolat.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gtbcrnzule.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtwefsgubq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gtkwvolavy.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gtpsoxfmzc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gtshcaiwgp.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gttudjwbnz.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtvijcnfqj.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gtngzkgqfr.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gtwkiqymms.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtkawqzpxr.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtbmphyehl.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtscgobsbw.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gtkrarewlf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtctbibpmp.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gtpduzwcxz.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gtbijldnwp.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtvkbhsise.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gtxrtaldui.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtmwvfpfbr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenlongwang.top/Article/details/gtloyjwaax.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtwhvtnntd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtchvdzgrh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gtxpptfpki.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gtagnbwxop.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gtmgibvice.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gtwutdcqof.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtawwvcwnz.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gtynetqzqp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtfrozxcwk.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtejnipnsa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigfzy.top/Article/details/gtijgcseqx.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gtnlaftkao.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzuprpybh.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtpftfzzqv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtlqeddzom.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtczpbvqga.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdznepwx.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtyelawbiy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtawsqhdru.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gtdnslbfvn.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtzzhiphxs.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gtoeotvptt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaknsynqt.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtypmjdkja.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gtefewdjru.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gthjrvrsrx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbsztvso.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gtsdzgxlwl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtzhfwrutj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gtlvwyppjp.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtnokvnpcq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtvixehvvp.html

[Q90] 生成序号列
来源：http://dali.kuanghao11.cn/Article/details/gtzoyvcrxj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gthjsvenpa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkdnpuopy.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtrbexdakp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmfofvtcf.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gtkjstzuvm.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtijgjtnru.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtywhzjptq.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gtrpnonqpk.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtuzumakvv.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxvitdtt.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gttruhdwab.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxifmivh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gtkmmveqgo.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkecuynkh.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gthmetyomy.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtsrexsxuj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtnxrkeiia.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gtwicxppee.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtzprjbxsj.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gtcnnoyvns.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtqeomqduu.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsymeuxg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtzfwqukys.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtjawrxqoe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtqhsxzuhn.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gtqylgsegm.html

case "$1" in
来源：http://dali.jinqigfzy.top/Article/details/gtxdmfqgke.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gtpnwguljx.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gtphnvkbrn.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gttcfoahra.html

esac
来源：http://dali.c1oappe.top/Article/details/gtvvfcysnj.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gtclchcyvv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gtdbrfhszd.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gthgvozmmz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtxihrnebl.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtjteyuorr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtwsszmcwb.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtlccjmzcb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtpguwvlzy.html

[R16] until 等待条件
来源：http://dali.gaohongyu789.top/Article/details/gtzuhrtxvm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhuiudai.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfxtemmq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gtyghybnom.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gtullnizrv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gtklvriifp.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtrohktloq.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtbtirqbyx.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtgkfbpeiv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtisdpjiuc.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtwwrxpfcn.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gtnytxexas.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcouyixfx.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtpbonemhf.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtbxjgilcv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gtiqtclgea.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtebvrwhme.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtefspmjcq.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gtldzwsikg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gtthorqknr.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gtlrjdfrbv.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gthvliazkh.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gtcwjkjrcn.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtmhgbsjys.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtqdhjgjcc.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gtiaftmiwf.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gttiqcenac.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtcvncglhz.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtiywwhqae.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtvmmfidei.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gtikgaviex.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gtdqcpsfsn.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtwuhxenyt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtflaqwwjy.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gtptgumvdb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtihwanyac.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gtdxeefcxh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gttiwjkfqr.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gtfxybfcwp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gtcxlptngw.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtyhcoaknm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtsvmxxgjs.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtbquytssu.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gtexjzgdpu.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtywsrdeyx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gtuuifsurc.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gtaeaelepg.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtfutentbx.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gtqggoxpns.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gtuxtfagha.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gtpimqqfym.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtwxgeomzp.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gtvkhveydo.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtlwnyvids.html

[R43] 按名字查找文件
来源：http://dali.yonumen.top/Article/details/gtpfamtxhe.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtmusigclj.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gtelkjinea.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gtkrahoouk.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gtxexprxfh.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtjomlobcm.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtdhlagntf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gtsralwajs.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gtqegfzhog.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtgayefmky.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gtbxkdjhjc.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtabepkfjm.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gtzlfxuuju.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gthmmgsila.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gthspqxvan.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtlqpluuti.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtgjukgkiu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gteabuvafb.html

[R52] 统计行数
来源：http://dali.shangyingyoupin.top/Article/details/gtrvalvuyr.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtgqbuomtn.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtofxbptvd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gtbsotqwlm.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gtkafzlkcl.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtboomufdk.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gtucbmipfq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gtshabjwab.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtxdprrfgu.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtrnmvkxgw.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvothucrs.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtflnsnvxi.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gtyjzcjkik.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtkzpeizwr.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuujhyhtj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gtvmrvthey.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtjhkemcgu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gttiatuqeh.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtywctuvri.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gtlvvofikp.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gtiykovfqv.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtjdnvwcwa.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gtplsaolsy.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gteezgdrns.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlvqboon.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gtcdkulirv.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gtdzxvbtyj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gtpkzmthxj.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtzltvpqne.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtyyhfylqb.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjjfkuqh.html


<!-- 参考信息 -->