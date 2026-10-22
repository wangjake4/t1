代发 wailian999

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2hsacsgxt.html

[Q16] 查询指定列
来源：http://dali.ybcxt.top/Article/details/gt2geqkfggz.html

SELECT id, name FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2tqbwnxvu.html

[Q17] 条件查询
来源：http://dali.bjfxy.top/Article/details/gt2ocskcoec.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gt2kznjxfmn.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gt2dwrlrlwz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gt2fowryecr.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gt2xlyspwgs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnfgnjvo.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gt2yhqbvdiu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2owaxgnbl.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gt2rwkqcynv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gt2dujcdizy.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gt2tmiubywe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gt2cuzandds.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gt2apfvgoeb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gt2unrbcife.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2lsvombtw.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2pitfelmv.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gt2qclhxygb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigfzy.top/Article/details/gt2ewhsozmu.html

[Q26] 计数
来源：http://dali.tanke756.top/Article/details/gt2nkswmqqz.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2fcgsuask.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gt2jmbauruw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gt2bejgnuew.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gt2cwtqftyd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2ecqfzayi.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gt2xkiidytz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2cwidbkih.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gt2ptouijya.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdyrhqxg.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2ldnlmynb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gt2afqxpkby.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2hsoumazz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2snrgohee.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntomcezh.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gt2qtmfabls.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gt2yqgblroz.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gt2ielvojmv.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gt2oybbjzmq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gt2ypyjukya.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2dmmzcyoo.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gt2gihfmpfh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gt2jdsmwxgq.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gt2jmgipriy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2podncxoo.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gt2bugdgtrq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvavxzwz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gt2gjgrierh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ehwqpu.com/Article/details/gt2pntcbvep.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gt2szonzzoe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gt2uruedylv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gt2tuswkmjs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwhpnxnz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gt2ljcyhdes.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxbvufut.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gt2ekxxpnux.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gt2jdrswtay.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gt2boyxpydn.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lecatwar.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gt2sapautlp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gt2qnpesqkx.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gt2ehourwza.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvihgeld.html

[Q44] IN 子查询
来源：http://dali.gogol.net.cn/Article/details/gt2steugyil.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqfwqaiy.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gt2afihvcdy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gt2xnzxadxr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gt2ppzovtyy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2wrbkjsoh.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvyxqtgo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gt2alettbui.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gt2dbsibnty.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gt2rijxlstz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gt2bzdldzav.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gt2rjqmfmrb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fodbklta.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gt2arezkusx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gt2ogxwraja.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gt2ghmpdzcb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2tdcyvryz.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gt2nrrvtgwf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2amgysmjz.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aklysuwo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gt2ujfdogsm.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpkrduur.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gt2tpceckjz.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gt2aounohmr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gt2kyjptabz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cheryme.top/Article/details/gt2fkganybp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gt2ppbhmzgb.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gt2lmhctkcv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2ycqmtxsx.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gt2kehzhiei.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2xjnsskpj.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gt2cphozchp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgpzbdwd.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenzaomai.com/Article/details/gt2gvgwwhld.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gt2peefcrfk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2yhclrwct.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gt2goapaxam.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2kizcjoud.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gt2hclmtmpr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jewjnizn.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gt2vscvzrad.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gt2anrbkwpk.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gt2aypdburb.html

COMMIT;
来源：http://dali.jinqigfzy.top/Article/details/gt2ydtgbcys.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gt2fssjxuuj.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gt2rgeenddo.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gt2wysxehek.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gt2gvqvyaej.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gt2zyjsfnxj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gt2wgcarpho.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gt2dgbstndz.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2epmsupeu.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gt2hwunqjcr.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gt2yicwhwxc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gt2gsggpgah.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gt2gihfzglg.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gt2emwqijfi.html

[Q71] 查看建表语句
来源：http://dali.jyoumei.cn/Article/details/gt2rkqmwjkq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gt2lifcvvog.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2ugtsesfe.html

SHOW INDEX FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2pijitwaw.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gt2xabfserv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gt2inflmkcl.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gt2zahewjwp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gt2ifppexcp.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2wgzbllet.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2sjgwnvon.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gt2pzkzbivr.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtlrfzuq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gt2kyrekucf.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gt2sjngklhc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gt2hhmhcrsw.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gt2enjlqszm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrepstlp.html

[Q79] 字符串拼接
来源：http://dali.meibo888.top/Article/details/gt2eomzplkc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gt2yygcapwp.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gt2ebzzzpzs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2mzraagby.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gt2mgvxzhut.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2cpfajcop.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gt2dytvdlbs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2qiuzfclh.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twkzqmer.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2zknqpwes.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gt2dylztiss.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2znndghmh.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gt2gclmajph.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gt2lunjbeki.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gt2fgvjgich.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gt2ovrjrjde.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gt2lggvlpbv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bsdfytzh.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gt2kprnuiva.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.mhx1999.top/Article/details/gt2abuhtraf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gt2nxsgsbnu.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2jzcusyuc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2ypknqckb.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gt2xotskfvn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gt2gfmimxsz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2urejtogn.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gt2quzckilg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2tiyeswex.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2oykeoums.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gt2ldspmodo.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2fbgmcygc.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gt2tdxzwcto.html

name="Tom"; echo "$name"
来源：http://dali.wangdashe.top/Article/details/gt2jgynqrdl.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gt2truvmaso.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gt2cfvngpvp.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gt2rosbhoub.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gt2ctzkbzjb.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gt2bfheeaaj.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gt2voarekph.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpqzjtyr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2pwehxxnb.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gt2hjkcyzak.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2krxelfrn.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gt2bnzwvbmi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gt2vaanqfsy.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2fbcuibyn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gt2zqqmdrdf.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rotlywaq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gt2extjsswo.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfsvjxlu.html

case "$1" in
来源：http://dali.jinqigfzy.top/Article/details/gt2tbcilupn.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gt2otrzhpfj.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gt2bwzxrmem.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gt2wzwjsffl.html

esac
来源：http://dali.hywenlv.cn/Article/details/gt2qrsqwvve.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcedpmlk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gt2irevrgto.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gt2bykvpgud.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2arvdwgnw.html

[R14] C 风格 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzyanjon.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqvcywp.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2iyxhxwam.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gt2avabhbhu.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gt2lrkgwruf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gt2kcmldpsd.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gt2gmlvdzcd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gt2ayqnhehi.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gt2tmdnbfky.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmxizdz.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gt2otxazxfg.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2fcfigzoq.html

[R20] 关联数组（字典）
来源：http://dali.hysaishi.cn/Article/details/gt2gbrooyrm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.c1oappe.top/Article/details/gt2anzdinax.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gt2lwepjbyb.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gt2oskuucpn.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yejjjnps.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gt2twtidntv.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwnxvbbl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gt2trnhvtxz.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2hmckkuex.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gt2qmlzzctp.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gt2abokzzan.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nyxvrjkq.html

[R26] 命令替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqykhtii.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gt2wdyjuwfm.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gt2nlorydyp.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gt2gcnsbwcg.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gt2cdnryphd.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gt2hdnlkave.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gt2qveyxsif.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gt2tlyfoqlm.html

[R30] 函数返回状态码
来源：http://dali.sxryk.cn/Article/details/gt2bdbkyxyo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daxiang520.top/Article/details/gt2szmdsmep.html

[R31] 局部变量
来源：http://dali.zdqjudy.top/Article/details/gt2ufmlcsif.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gt2zmzvapxg.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bakzmedz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2egwuyztm.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gt2rkpzznev.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtbtlrdy.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gt2knduqhbi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dudtnlxm.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gt2rxbxofhi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gt2jjyhgrgp.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gt2cukksscl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gt2sgphlzqh.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gt2ekypupjj.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2wjttzksm.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gt2qhwsrugr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gt2ehxnuxrc.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gt2mqjqbihh.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2rwvuvgoh.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gt2xcqdcdih.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gt2plppivfh.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gt2wexcjtgk.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncvanmws.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gt2wakesnfq.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gt2pguyymbx.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gt2xtwrqmmu.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gt2vlwwoskf.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gt2xdcfwvlb.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gt2piyrmdut.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gt2kwvnutvp.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gt2ubltmrun.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqxpfslj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gt2reetvidy.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gt2bjvfmvgy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2knvifecj.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gt2krienpxp.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2dttcgwyl.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gt2yjtaylfn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqlclgss.html

[R50] awk 求和
来源：http://dali.xuanzx.com/Article/details/gt2eurtibcv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2vgphxlpi.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gt2bfvpmbpk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gt2olnxodmc.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gt2qqpuzrvi.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gt2sttocfst.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gt2jecqrnaj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gt2xjjglgzs.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myvirypu.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gt2gcdytlqj.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gt2lkasnvjd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gt2kvpxppvd.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gt2jfulhnqw.html

scp file user@host:/path/
来源：http://dali.snrcjt.cn/Article/details/gt2xhcfhahn.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gt2xzfgasfi.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gt2qfyeqvwf.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gt2njnlcaxr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gt2zikrnrsp.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2colrkwvx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gt2zhkslyzz.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2odonkkbv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gt2hpxdpqkx.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gt2jhxdyzhc.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gt2ovdduzhr.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gt2qtbqvhvz.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gt2dzfoffgt.html

[R63] 内存与进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jducsbng.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gt2bervtggu.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gt2aebschrx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gt2sqrgfate.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gt2tfasezks.html


<!-- 参考信息 -->