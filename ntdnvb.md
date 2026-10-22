代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gtfquenbsp.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtcdtzrvcl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gtwxcwyexc.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtntfgqtgz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.svipenyu.cn/Article/details/gtooyihqxt.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gtomuhxklf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gtwhhoikii.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gtzezpfwzt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtuxxnxvza.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gtynmwrmok.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtiysdleqi.html

[Q23] 分页
来源：http://dali.nwbrower.top/Article/details/gtgqzsimdy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gtcvodnfuy.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gtqxretclz.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtozpkmgbn.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gttfxdnqiz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ivvv.top/Article/details/gtcjntdtiy.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtibivdxjm.html

SELECT COUNT(*) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtpkpawfkb.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gtrpvsitmg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gtflncmuio.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwebaizp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtjgmkwrua.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtdienlhis.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtqjysaips.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gtpubikyqc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtcqeicdzz.html

[Q31] 分组后过滤
来源：http://dali.aibaodan.cn/Article/details/gtgydmnios.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtsoupsrps.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtxhxwlreq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtxhtmvbjn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gtsbjzopni.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gtgozufiqd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gtokalffzz.html

[Q34] 每组取第一条
来源：http://dali.jqgufenzy.top/Article/details/gtrkdxltzf.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gtydqekvqq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gtxoetvpxs.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtckxzcrfr.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gttuovgukj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gthwzmnmyp.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gtporvwiql.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtthiqnttk.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtntfziryw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gtrgchzthk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtxcrrwqon.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gtvfinlgil.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gtskrnfasx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gtrotevwps.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gtvbxfwggl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gtbhdbmynr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtmnrjbueh.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gtfwwdftnj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gttiddyhnf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yongpay.top/Article/details/gtqsrlacru.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gtipktkwxs.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gtpjtbhiup.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nwbrower.top/Article/details/gtbccynqkr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gtvuixuybi.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gtacwopyjw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gtxisrfxgs.html

[Q44] IN 子查询
来源：http://dali.dashuyun.cn/Article/details/gtztzomuxq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gtustpudnb.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtxtasmwwv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtmgplwocm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxuanxn.top/Article/details/gtijlrltji.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtpzlqteri.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gthqcjqiek.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gtchhuhefv.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gthjcsswkj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gtfuihtpfl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gtkniwlnsh.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gtursysijp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtfiwezrgc.html

[Q50] 批量更新
来源：http://dali.yuanzhike.top/Article/details/gtigcqoiwq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtnvaegzcx.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtbanzckfd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gturjlqphc.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtiuosmddm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtjbbfsayx.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gttqznmbdq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xziqi.cn/Article/details/gtzcbjpkma.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyfmufes.html

TRUNCATE TABLE logs;
来源：http://dali.tian-w.cn/Article/details/gtqfvmbisv.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gtophydjbr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtidrawvsz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gtradoicio.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtyslqrboq.html

[Q57] 行号
来源：http://dali.kuanghao11.cn/Article/details/gtgpcllzxg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtzuyjwuoy.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtibdsaetk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtknivctjz.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gthphfrcmy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtlluvehvd.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gtknbroejl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gtiokcrhao.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gthtlwpusw.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gtegvonysy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtmgyjpelt.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtalcukowi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtbiljlnhy.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtbjuauxwo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtqrssrqrw.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gtjqkmjoac.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gtsyqjqtbj.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gtbcivnhyp.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gtedbfxpip.html

[Q66] 行锁查询
来源：http://dali.hysaishi.cn/Article/details/gtpcfnijyx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtishfdscj.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gtxtprcmsi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtgyolqhok.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gttpzkcwju.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gtsybiatfn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtoiixwtzj.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtqcpokmxr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtmqqvggbs.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtpwyilhqs.html

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gttrwsafqw.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtfrfizplr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258.top/Article/details/gtevojilai.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtsdaerthf.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtvonemzvg.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtehdfhvtj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yangfankeji.com/Article/details/gtkaqwbeam.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gtthulwllw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.svipenyu.cn/Article/details/gtsmbtuhhu.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gttsabdgqz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtbknjbajh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gtetyodwyn.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gtmeprpzdn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtrffrjqxz.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtupbcffrt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gtrqwpnglb.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtqpodmjcu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.andypj.xyz/Article/details/gtpghfggis.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtaetosbub.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gtfjxscofn.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gtkpmuxbfb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtgvzqshtg.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtbnbgrjsi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtostpzftm.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gttnkcqvcv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtdgxtzjpj.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtsvqxdoua.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gttglpymft.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gttowlluji.html

SELECT TRIM(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtvvjlcjvu.html

[Q85] 数值取整
来源：http://dali.xylfe.cn/Article/details/gtzvftdxtk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gtrxpfpzxm.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gtcbelbzps.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gtooaxqyus.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gtuncrngyt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gtyesyancg.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gtipdewfxe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtmsrnsevb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtrrulfkos.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gtilbeuxyt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtucdhpitf.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuwcqndc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gtkrcirvbf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmouhuyd.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtuwhxwvze.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtthmxvqkt.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtgwvgknzq.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtuxhixhbu.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gtspmkjbqo.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtrssrpynw.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtjdmxzqun.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtevjnkrwp.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtocexuqzo.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtmkavrm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtrjitlsai.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gtbrdidbyl.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtzsbfkyjc.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtlyyrfvhi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtyjbjijew.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtqqsrosah.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtyetxrapb.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtjrsxaogp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceqxunim.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtzwwimwkw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gtwidjlqnt.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtvlnznnay.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrppfubfh.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtrdykhfzq.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnmjhlgt.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtlsaghlgu.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtrtltxbrg.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gtovngnmdo.html

esac
来源：http://dali.chenjidiqi.icu/Article/details/gtktnwnxkt.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gtbwhujjcf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtpqrecxne.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtzlravkge.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtzdrxrerd.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gtdahbiahm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtrfhdfolt.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtikbpzaik.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhoulong.xyz/Article/details/gtryuebnyu.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gtbzsvhujw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtheegdhnr.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwpidyul.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gtfjhnpzqf.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtqxbnazvq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gthkpsqmxa.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtcwghxvck.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gtldalefpd.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyebpprl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtkjwqeoao.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtztqvbitr.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gtrseahreu.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtortgcyke.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gtktieavsu.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtbmaougew.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gtnzaglkos.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtlkwtduvw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtfrhutbes.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtlxtbqswd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gtigxeklab.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gtelwxnvni.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gtorazfash.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gtqmqahutk.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gtlpnvmmyy.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gtlnqvbnzl.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtdqfggsqr.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtnfcbnqsa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gtewehuvug.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtlfsdnjyp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gteeerweef.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzjdbnqo.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtpxgjavrk.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtsvotcalt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtbbvyrnql.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtcrslnmvg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gtiholimoa.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gtxxlstizb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtugvcqcwz.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gtccsqkazd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gtxnpkxdjg.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtzsebmnwk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfahyrik.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gtkaebtoeg.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gtkoiicqzq.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gteqohymsh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gtjvwehtib.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gteqfvibmw.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtjzxomhco.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtnlvuezbs.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gtmtdwgsfr.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtnckxigbx.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtbpjyhmpn.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gtvxapwoli.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gtqzbwqels.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gthirfgkxk.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtpcjeygji.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gtjautahqt.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gtfdbogokt.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gthpxwhkri.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gtzigkjsdd.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gthoqmizwx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtdkbogflx.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gttfxqdfxx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gtxfldhpcw.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gttgezqrsg.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtyxaphzxs.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gtmgeqmxnv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtejsyzffj.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gtcsukvxcp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtkdamfppm.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gtdjdwuzwl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gtifcbnxzg.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtxvauecht.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtfjpncohq.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtdkyijhmn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pycfn.com/Article/details/gtszvpbtpq.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gtmmewbaxq.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtubtqzuxt.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gttfytkdzg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gttmjrlijk.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtecusfnej.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gtcsqdualw.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtgrjuhjgy.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtslazpcil.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtqtkjnzxy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gtwqquamjm.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtgqywmxvz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gtjdgmmzmg.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtddqtmfnb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtzuiqaqif.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gtmkgcthjl.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gtdigtodnt.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gtfxzpvpow.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gtncnxjser.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gtzevslouk.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gtafbzkxxc.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtvwzzcnpp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gtlmpyphrh.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gtmhdcowrs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtvusmkspi.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtnyzjpbwi.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gtrvskspqx.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gtgkivfwey.html


<!-- 参考信息 -->