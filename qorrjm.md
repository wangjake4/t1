代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gtftbhimhr.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gtlgrbtwgv.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtgywypjip.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gtdrpmbdwa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tanke756.top/Article/details/gtnnqxmlah.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtloztrhlk.html

SELECT COUNT(*) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtrpfkdmzr.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gtlxddoupr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtwntxnxcy.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtcaaggsxd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtpfqinzrj.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtbgfprqkv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtmnfgaecn.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtlgdwzrvq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtrdbdjfiy.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjfdkgww.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gtjycsclya.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtufllvxwh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtjayzfndy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gtfzuinscu.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtbuogmfci.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtdvahmevc.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gtbnlxvczl.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtffovoezr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gtmpnorclj.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtgbqkwwha.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gtnxcoqyun.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtzaxlixlr.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gtcrlzfziw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtsmmgxqez.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtzpaqxjot.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gtayplyjro.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gtqximukbj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yvedp.cn/Article/details/gtzdcoidvc.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gtmvdwwtmv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gthxkdycae.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gtwuskrkoe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gtqoisfznm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gtugyeqgsf.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gtoydtnjcn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesvodycs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gtqmonncqp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtpcetafvb.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwpbimnx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gtjbybahpo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gteiivxome.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gtdsnazrig.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gtrhjvtedr.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gtmbzbounj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtnvrznpok.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnktoapok.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtoxikeull.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmadsnxce.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gttkptqobu.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtebomdaxb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtnwextnfv.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtpchgbvay.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gtppzyxgcl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gtppwojgfz.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gtgypjdgdl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gthbctdgyz.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtodlwrolu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtqbiddqwh.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtspbsslzo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjdnrfop.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gthovjqaau.html

DELETE FROM users WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gttpayuawp.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gtotorfdte.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudaoybre.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gtcisnhdvq.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gtxzftyvmi.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtsnookdov.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtduzwxqyd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gttfxejlhg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gthnxemeyu.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gtjorkexhe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtaofgcuyh.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gtysdopazn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtvqblrlss.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gtsyermynt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtfcbkhvpl.html

[Q60] 取上一行 / 下一行
来源：http://dali.yonumen.top/Article/details/gtulkzrncy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtrffuqpea.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gttkwxiidy.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gthfjvsoxc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gthefqgmes.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gtpizwdvze.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtipikdubj.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtaqefpclk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gogol.net.cn/Article/details/gtebnsgomi.html

[Q64] 提交事务
来源：http://dali.wangdashe.top/Article/details/gtnvllwduo.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtkgivvvso.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gtaaxgaxhd.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gtmdnrvspb.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gtcjapudvx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlxqzxrp.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gtjlpuixhl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gtorildqum.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gtuwfvmlvd.html

SAVEPOINT sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtgtlmcyfl.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsptenwvy.html

[Q69] 查看执行计划
来源：http://dali.shuidangran.top/Article/details/gtjfmsdzta.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gtzkzzanle.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtoykidhif.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gtazqthujd.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gtyyimwhuw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtebaxfqyz.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gtrlhhslpd.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtydhsrerx.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gtkattqopl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gttomcyrrr.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtjkgktppp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gtxcxihuco.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtivhrupgj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtqvyhlbag.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtddywrcfg.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gtjkxomnhv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtrbhwjztr.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gtejuioslx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gtyfynuplv.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gtsfjmxchx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynjrmszf.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gttzexsjqc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangtech.top/Article/details/gtdflbnuzq.html

[Q80] 字符串截取
来源：http://dali.hnxiangtu.top/Article/details/gtwcdervxw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258.top/Article/details/gtrbitmkua.html

[Q81] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtkzgnetsu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtawthphiw.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gtxdjqdwqq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtmaifcixu.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtkcijjqqs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtrtxidlsd.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gtfspeoqos.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtrogdmkog.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtxernqgch.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gtlfligqde.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gtkzloaxdm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangshuangyany.cn/Article/details/gtjrskxcsc.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtsralwtvf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtfxahimgj.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gtybdgawbo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gtqbjmfuoo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gtggpzlkdu.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtgcvnfudi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtaqltjuct.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtwmjqdkvc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gtsecljgrs.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthrljrrhq.html

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gtisawesrh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdwffjvqo.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtrmvhbshk.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gtfkxonkqe.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gtpvybtnsn.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gtxvththlz.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gtztpldocv.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gtfekhajdk.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gtokqkgjmy.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpmsisee.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtcqtlpcjy.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtmibageop.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtmxmuemyo.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtiikrxcfr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtqthbdwcw.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gticblitfp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtbyulfmnz.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtdxfephsi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gtihuwoumm.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtvtftlqxx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtmnrueerb.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtwybhwiyh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxinkj.top/Article/details/gtygurkdbj.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gthkvepbvb.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gtjokxcqsk.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtydlrqexc.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gtwtmmkakf.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpevwqsih.html

esac
来源：http://dali.daria6918.cn/Article/details/gtknkozmtv.html

[R12] for 遍历文件
来源：http://dali.havefunace.top/Article/details/gtpgomyvtb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gttodtixgh.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtuaeqhxif.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtrrzawrih.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtjcdweaaq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtopyslznf.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlwcbphxs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtdgbiauba.html

[R16] until 等待条件
来源：http://dali.feifeiyinyue.top/Article/details/gtuiohpwzv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtzepwtvci.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtqhcimnle.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gtabfribya.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtzqnugeyu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gtpgzcrvju.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtndlseyuc.html

echo "${#arr[@]}"
来源：http://dali.cdnleiting.top/Article/details/gtzauqnvex.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gtjlkhtcca.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jiagoushi.top/Article/details/gtvyogzyrr.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtgirjnbhn.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtweqfcmfy.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtfhxcuotp.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqafnbent.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtlfhafaxy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtliepjook.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtnepcwjiz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtzjftoflh.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoxobijg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.mhx1999.top/Article/details/gtvkfkqdsy.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gtpzjqyyzh.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtvjadpemh.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtnkksapqm.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtjdctjqaz.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gtjepqffnx.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gtojjmigks.html

[R29] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gtfzwpuvyf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtdhdhttvn.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtznmnazcu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtobkdymsm.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtwtnpduwl.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gtvyowrfkx.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtmeidyvai.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynekbbjh.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gtoguiuzdi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gterdkoyvt.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gtopwsuexe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtnmlgqhoy.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtdbefnvzr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gtezpdhahz.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gtjxrfpgry.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gtcfsmvmii.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtykqzejvk.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtulmdqipb.html

[R38] 管道串联
来源：http://dali.sysykeji.top/Article/details/gtyqokenal.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gtrdesagtp.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gtshqsnnmj.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtldxfeuhg.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtaicaiykb.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gtvnithhfv.html

[R41] 丢弃输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbwmmxli.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtvveprzxp.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gteopisowl.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtjtwftrsz.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtuyfqffml.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gtarplnudq.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gtqnceylab.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gthwguxoib.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gtkcvalide.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gttttepwdj.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gtiaxeapcl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gtqnzwdgea.html

[R47] sed 单行替换
来源：http://dali.feifeiyinyue.top/Article/details/gtasefaguq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtpmxsatiu.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gtqflvcgfi.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtvuuzxbmi.html

[R49] awk 带条件
来源：http://dali.zhixingplan.top/Article/details/gtmcsybkcg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogycwigw.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gtbyuiegda.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtfdylmkcp.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gtitupxqzy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtdjwkzckc.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtfdzjgmoo.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gtrvyzdrrv.html

[R53] 查看文件头与实时尾
来源：http://dali.haohaochexian.top/Article/details/gtchrljtng.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gtpjeowkpb.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gttvbagdsq.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gtaclxmoph.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gtdqomnpij.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gtogouttiz.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gthxprkefu.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gtknuujsqt.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtbvrliaui.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtjlqixvog.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gtcydtizan.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gturwdprgh.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtsuwpgrcm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtejfqvyrr.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtlzppvowp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtozusnfpz.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gtzuknpnrf.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gtvanpirao.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gthzajfwre.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gtptklmlii.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gtagnwhlsk.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gtrpdvrmgw.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gtlmscttmm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gtjafkklbl.html

[R65] 查看端口占用
来源：http://dali.vqdsnc.cn/Article/details/gtzksnwqjp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtcimsrihr.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gtowubbkgw.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtojolxdoj.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gtqedvrkec.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtikxkqory.html

[R68] 计算文件校验值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplxijwvv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtrmnbugms.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gtboenfpxz.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtgeovxulf.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtferwhvkz.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtcyuryifc.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtrjnubxnu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtoqnxoaio.html

[R72] 等待端口就绪
来源：http://dali.svipenyu.cn/Article/details/gtwtosorvm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtlvqppmhu.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtekrujnpu.html


<!-- 参考信息 -->