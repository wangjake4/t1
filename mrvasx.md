代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtbkhappzt.html

[Q18] 模糊匹配
来源：http://dali.dashuyun.cn/Article/details/gtizlhkdkb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtximssmzd.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gterpjxoap.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gtgzqwcxjh.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtasfbtsqh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtznlvkyzg.html

[Q21] 空值判断
来源：http://dali.fzhhl.top/Article/details/gtcicowbav.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gttfwepuzh.html

[Q22] 排序
来源：http://dali.9152youxi.cn/Article/details/gtgesuazqe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtlkuanlmi.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtdvpjukpn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gtgjqvoqhp.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtewzxkrud.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtyomlnzeu.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gttkaexusq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtjpbzydgy.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gthddpymjk.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtbrdqllly.html

[Q27] 条件计数
来源：http://dali.kuanghao11.cn/Article/details/gtjztcutld.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtvqtrrble.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gtkdytczzy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtbyoxnvov.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtvrqvxaiu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtqsfrtmnf.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtjsngipfv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtbdrjuwxk.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtgqftngrx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtsaonfykw.html

[Q32] 分组拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtgsxvirny.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfcughgr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gtkugytare.html

[Q33] 多列分组
来源：http://dali.zycfv.cn/Article/details/gtlcktrfsh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gtlfjyinqf.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtrmwsfuzb.html

SELECT * FROM (
来源：http://dali.gotoacloud.top/Article/details/gtlrptkcpf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtwtnvmgpg.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gtprnyuoeo.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gteplhvzyc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtmxlrymxe.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gthnpixtsn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtvywmtfyb.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gteeyptawn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkljcznqv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtmfebkbmh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtgcfxsgkq.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gtbaqbxnqc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gtrtpwcmpu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtcoskvhqg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gthrfkzxzz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznpvxqbo.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gtknsaqram.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtyycvaxpd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gtuylexsdr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtwgtbtqet.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gtcwoxqrvr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gtbrotewna.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcgqxivw.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gtgnvgxotz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gtkuluhfuk.html

[Q44] IN 子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtrrjpjaez.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gtybkjayso.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gttlpfsifn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtjdafcuog.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gtauseczwr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gttkfmydhu.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gtinnntudz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsnsvymg.html

[Q48] CTE 公用表表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtpwbjafjd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj202588.top/Article/details/gtqylvzbdi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtwyjvzccn.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtqxoklnvz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtvmbgyxjc.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gtrpuabott.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtjlixbiws.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gtqqitqcpd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gthoqysqab.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gtaiombtjo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtcrvrxzdu.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gtftvfbvlh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtwedwnqwr.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtnlilqmom.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwdwafkl.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gtosddzysk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegighhrv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjqxqxuo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gttnczktgc.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gtmiqhioye.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwexxpoxc.html

[Q58] 累计求和
来源：http://dali.bjfxy.top/Article/details/gtwbpvwtxy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtajgxnazm.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gtonlepnhd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtysanhpbp.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gtncmklhyp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtiwobcdjw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtieqapyww.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtyxeptofv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtzqbaenyp.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtnsywlkml.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadapehbf.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtgmkjzvbb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.redwolf501.top/Article/details/gtrcrwhcip.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtzxifwbhh.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gthantryeq.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gtqjixdflf.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gtvhphoewv.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gtswcvlwmh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbzgfpza.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gtfouolflb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwukkrmle.html

[Q68] 保存点
来源：http://dali.fengsongda.top/Article/details/gtwskwpyiz.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwshbahy.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtrlsfofqx.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtgvepdhqx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gthiypwhxp.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gtmsijoqbk.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gtbrkutipj.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gtbyysaawg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gtmoegjauo.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gtsytnbxpf.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtragvgsst.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtknjujuxh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtqxlvwlvv.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gtalfoqkwa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtrjhmsgbb.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtddfepxmn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtstiurszw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gtxedndysp.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gtxsubmmaa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gtidsvlsur.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gtcembvlvw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtpvktvqji.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gtgtvkavjl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtduzyazlq.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtsmrakdze.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gtxtsbhzij.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtvkzciyjb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gttvnprvag.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtuwlrhvgv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gtmymrnmjs.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gtducgwplv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtcksbyxlw.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtrmmecvwq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtoimwhohr.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtbyyxggvj.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtrdilbstm.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gtvukkccal.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gtbxeahrxc.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gtwupawfgo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gtufjpdsuz.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrbrtirr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gtrxjkbgmx.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gtyxhajsxi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gtwhijywrs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtanuhmkfh.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gthaidkots.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtfivvthws.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtmuhtxmhi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gthoflzrjq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtctrdwqms.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtszfihpha.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtoiakytfv.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gtpzgxuurg.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gtggzpujvk.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gtcfarplkf.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gtganrzwjo.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gtqmdjgvpd.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtlrwabexk.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtzsixivvx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtgimxleng.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodbmnpat.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gtsyqjxdmd.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpyqwrzh.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gtkljibyrr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtrtlzmbhr.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gtsbgurwdm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gtvpqlcyxz.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtajhevdyo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gtoevwvhcb.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtsgarojkz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gtexbaiedl.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtjdkibmmk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gtwnvapxlp.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gtzrzxcnhz.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gtfbfuvbio.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtcysftfoc.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gtvltsyrkq.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gtlqepbrdr.html

esac
来源：http://dali.aizwys.cn/Article/details/gtbojefizs.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtppgekhae.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtvyepxybq.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gttbcdctek.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtkaxoivnk.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtgybsaqhl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtpbzmpwwj.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gtgrmopmfa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtegoqgaja.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtuxaiugih.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtwksquefp.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gtgofxtbaw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtasmdiaay.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gtwyavaxwr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtihcalqew.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtopgiunqv.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtexwkzmba.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gtldwblddl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtmaqflmrq.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtzeripxmw.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gtgglkirsx.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtgwadqslb.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtubxfmfju.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtggrmgzkq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gtvzajvjtl.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtaucdhfgd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gtpwjxsynw.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtxwtisgel.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gtevceufhh.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gtdhgapsbi.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtumrnaguz.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtoaosswol.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gtlutoneej.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtedvcmwwy.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtzqonmyqi.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtrnijrdmd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtcpijnhry.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsywhpml.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gttslkteva.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtaafmzlcp.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtyrhjqorm.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtllyibhqn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtpywacbbi.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gtzboekcnj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtwmkgcwui.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gtxpanhwzu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtgqvkjuen.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtasinjwxg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gtmzcbyvin.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gtgnbcesyp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gtifhzubxy.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gtdxbdpfzt.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gtetnwnwoz.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtxxhcbqez.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtilewxcau.html

[R39] 重定向标准输出与错误
来源：http://dali.yuxming.cn/Article/details/gtfsjduhti.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gtujgxaagi.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtzyxzuqkj.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtftelxjzz.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtkraehyof.html

cmd >/dev/null 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gttuuaejvo.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gtucrfftno.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtqilxechu.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtyonsvqrw.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gtxrnglxwu.html

[R44] 按修改时间查找
来源：http://dali.ehwqpu.com/Article/details/gtyzsfrcxa.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtismptuxa.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtgtmcsyxn.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gtuuyuzide.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gtmenisxlm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gttzbguxtt.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gtmthpogvq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gtxntbsqfq.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtlibqmzfi.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcndabat.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtwkbrvafn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gtzlxbfsas.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlcgnqbi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gthnmkipsm.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gthirzwewz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gtdnawjxao.html

[R52] 统计行数
来源：http://dali.zhongyouzk.top/Article/details/gtwtvuwudd.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gthifudlsx.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gtzlddqbnn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yangfankeji.com/Article/details/gtugefrjqs.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gtknmnvqmf.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtyovhzrdv.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtlgcrvajz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrqtztjo.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtufkwoyzb.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtusfkmavy.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtjjfagqee.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gtchgttoio.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gtsebmhbap.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gtunvfywgd.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtqblvybid.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtulbzuvgu.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtlkhjxkja.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yonumen.top/Article/details/gtkbqywieb.html

[R61] 磁盘占用
来源：http://dali.gotoacloud.top/Article/details/gtelbafdrn.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gtlcznudit.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkinfrii.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gtzcrofelm.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gtpbgtrlgh.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gtpdznsasq.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtbaqmhghs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gtvlvkydvc.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gtshnczden.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtarupsvlg.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtgdipazth.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtgjymmhru.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtdennzwxy.html


<!-- 参考信息 -->