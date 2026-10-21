代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtjrcrrbxe.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtvmfnlcdg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtwqasxqsb.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtbkpmbexr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcngfsfp.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtnkvislmn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.meibo888.top/Article/details/gtklqrnevj.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtxobavwko.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtczfpfyxm.html

[Q22] 排序
来源：http://dali.kuanghao11.cn/Article/details/gtavtbflra.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gtcumokyhh.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gteqturexa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gthbpnlsbe.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gthzjqmhbc.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdukyman.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gthtybjdyp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guowangkeji.top/Article/details/gtvmmbtmpu.html

[Q26] 计数
来源：http://dali.tanke756.top/Article/details/gtsyxxzqph.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtznczgjon.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gtbkyethdo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtufsyplvg.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtsnlqtktl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtrmiczzsq.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gtnnkkihvv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzsvrulj.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtohxvxffi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtgjhmrsgc.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtzlpvwmtn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gtyauhycte.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtnzyxdghn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuasezks.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gthfbvguje.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gtdlxswcyj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tian-w.cn/Article/details/gtihlfcqul.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtwesftdnk.html

SELECT * FROM (
来源：http://dali.chenzaomai.com/Article/details/gtojesgdot.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gtgsjlygkx.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtibycluej.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtmckbnajv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtihpvfgqt.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gtzgtczmaw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtqirpakmm.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gtcnaucqux.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtvpsmnhuf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gtwsembfeq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtssmnxbuw.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gtnoycmavj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gtxerxplhu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtsxfgdgyf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gtzwxibplm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxxtpfed.html

[Q41] 多表连接
来源：http://dali.chenlongwang.top/Article/details/gtedictxbc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtefzoqvkw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gtzlblvidg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cheryme.top/Article/details/gtcnrjrweo.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtebowvazc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtpqxgxzwm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtznaejldm.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gtrawjpusp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gtbcxojnly.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gtinuogvtq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gtdkuyghpx.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtdyepetyk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtbtlohisd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gtvbkkrogn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtukhknsnp.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtdoxecgjq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtiieetyzq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfwvecoo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gtjcrxmlyu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tanke756.top/Article/details/gttshxglxz.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtsuqeefcs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvrhlwhm.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtwaktvzho.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gttcjstqau.html

[Q51] 用子查询更新
来源：http://dali.ivvv.top/Article/details/gtoejiwzzm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gtuekehxzw.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gtxlgtippq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtupafdjfj.html

[Q53] 按条件删除
来源：http://dali.svipenyu.cn/Article/details/gtdpmvdick.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gtjsmevfvo.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gtrjvnmmfs.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtfecmhhwq.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtgfgojxrm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtbicjpccv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.0kj1m.cn/Article/details/gtidmwmlel.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtmltigerg.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gtogwaqome.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gtqqaagkra.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gtlgykoaun.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtfppzavxq.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gtzjogfrbz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtvasulwrm.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtajqjjnwx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gthgocpxyt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtglajbils.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtrqrtlvna.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gthspmqkdu.html

[Q62] 分组占比
来源：http://dali.zhengqikj.top/Article/details/gtjmawvbaw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtxztrbmbz.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gteksjxgol.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gtdaegmfpf.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtrfsntxcy.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gttgergdst.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gttkbulmjm.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gtageckpst.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gtpmceaikx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrdlgqsh.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gtlptbjliv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gtxbvazfdh.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gtxqzwwckg.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gtwqyeduxx.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtfnkcstdq.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gthymahicy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtqnkzlhfy.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gtsomfjorw.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtsrskvkvw.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtsqtleejv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gttstpsqrd.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtmarcrxle.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gtrzmmqqls.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gtzvnbtsxu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtqcemuoqv.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gtttrkuijz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtzoiwwfom.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtkixipbow.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtofextepm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gtrnfrzexw.html

[Q76] 按天统计
来源：http://dali.wangshuangyany.cn/Article/details/gtafncbttd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtwrsuunna.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gtjbpoonld.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhengqikj.top/Article/details/gtryujgjcw.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gtudpsbldl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gtiyqodlbf.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtdigkexgr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangtech.top/Article/details/gtraigcxus.html

[Q80] 字符串截取
来源：http://dali.cucudq.cn/Article/details/gtiudtobjt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtestgqahk.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtqzjcoxcq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtkjmwzdgt.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gtcgmsjxtr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtzuncypoz.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtuldchyfd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtcwpxmone.html

[Q84] 去除首尾空格
来源：http://dali.aizwys.cn/Article/details/gtfinbzykc.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtnwvivjlk.html

[Q85] 数值取整
来源：http://dali.mhx1999.top/Article/details/gtftbkhkvd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gtacmfioop.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtpneacx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gtxckxolsc.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gteteueycg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gttcfmnzud.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gthgtkuurp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtcurbjzck.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gtrooreftx.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gteextywhb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gtuqsmorll.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gtnkiamieg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtxrykneul.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrbdyatau.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gtalcgvbfj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdtlqwakr.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gtkjvpwhmn.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gtlpjnlrud.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gtkznghyzp.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtwzrbtiow.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtkqdjykhm.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gtplqneegv.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gtxcwwrpxc.html

[R04] 位置参数
来源：http://dali.cucudq.cn/Article/details/gtkxyqkfux.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gtptspacil.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtkgggbioe.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gtstbmiskm.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtjdjalfmn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtjnljphkb.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtfailpiwk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gtplwqhhwy.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gtirgsyejl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gtqrqfcrtu.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtguuzmxlb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gtnrqlljky.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gtcljyheof.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gtigxjckwx.html

[R11] case 多分支
来源：http://dali.ehwqpu.com/Article/details/gtcfysomau.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gtsyxfmmfu.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gteamgtxqc.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gtnijlcdcf.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtetfnjivt.html

esac
来源：http://dali.ppjwa.cn/Article/details/gttjxsqrbd.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnbhasjhd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gtsgonvjac.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtdrkthqsg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtfcvftqlz.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtirrenwbp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtxnjcklma.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtvfpcxtqy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gtzylhtcuj.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gtuoqpqiem.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtfqpwvhez.html

[R17] 数组定义与取值
来源：http://dali.yj20258888.top/Article/details/gtldjsdboa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gterffrhgz.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtwbwxyvlu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gtmeiodsds.html

[R19] 数组长度
来源：http://dali.cheryme.top/Article/details/gtawziqcjg.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gtqktjfhru.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gtahpnenoj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtsozoirsb.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gtauagzzin.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gtlhqtgnts.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gttxzhxynd.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtqfxsgmwv.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtujwvfhcj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtiroomvvn.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtkdxkycog.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtbymaozxz.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gtqxuadlkn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gtogeaweej.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gtcvnsygnr.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtqvntvlso.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gtzhxeqkaa.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtjvsiksyo.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gtvuwaeafq.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gteauxrafr.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtbseslqyn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gtsvknudni.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtkidwmrgk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yongpay.top/Article/details/gtyvtcezrc.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gtnghoerdo.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gtadvjhusr.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtjdxlmqwu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gthywfptcx.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gtegvamzti.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtdijitell.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gtophofcnk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtyowojury.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gtgewurwjh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gtnszshein.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtkasepfba.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gtabscupeq.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gtpfhmhnat.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtmzuxxfzn.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gtmpctmcpj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gtqjwbvjqn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gtongjogfs.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtpomkeeow.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtcikulyzd.html

echo "log" >> out.log
来源：http://dali.smart0.xyz/Article/details/gtzijmdiau.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gtcvopgcbs.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gtjrguwhvk.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gtvgccqicy.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gtnmqfhcpr.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtxjlybhlp.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gtjrlqlqst.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gtsbujporh.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gtkhutuzex.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtnczisced.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gtqjwbysfx.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gtcdlchbeg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daria6918.cn/Article/details/gtgmrpgyrc.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtwiugosxi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtcsasagor.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gtobimsjky.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtkwkxoovy.html

[R49] awk 带条件
来源：http://dali.jinqigufen.top/Article/details/gtoanjzmqh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gtykngbbgp.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gtmdxwblwk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtyizriiwq.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtvldkofud.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gtkkwvzpvy.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gtyofwyqjf.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtgqtlmwyv.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gtrwbljrus.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gtpodvciso.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gttqsrgrxl.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gthscgvsiy.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gthuudriao.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hysaishi.cn/Article/details/gtpfszsmaw.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiptehzer.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkkooafs.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtjgiaehax.html

ssh user@host 'uptime'
来源：http://dali.sufxvd.cn/Article/details/gtvxpphybe.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gtmrzqjerb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gtzbvmcbgu.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtqfcuicku.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrantceix.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtovehdbjh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gtmsjhjtwk.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtbofldvax.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gtspyhwmef.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gtjeljjjyu.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gtaclluujp.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gtzvtpfuxy.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gtglsxrovx.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtnxqsjind.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtpgfrgyax.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtanvcjbit.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivvobzxf.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtvowjjbfv.html

crontab -e;  crontab -l
来源：http://dali.cqqwz.cn/Article/details/gtgrwjaufy.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtgpjxgidn.html


<!-- 参考信息 -->