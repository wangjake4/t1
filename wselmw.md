代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gtvncyswtn.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtmcodmfwg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtlbhcnluk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gtcefspmkq.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gtdkmutxas.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gtcelrfsjj.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gthtmuesym.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtpzymmtfs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtoaxcpdif.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiinzxvtq.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gtfrqefkdd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtdgvmerbq.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gtdkbopzbq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtjnshfkgb.html

[Q37] 右连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkdxucfe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtongmmgmc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gtjdybrbmf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtpldignth.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtlbsuiodz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gtdatjmins.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gtayffunje.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gtckiuhvww.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gtrwpyghyx.html

[Q41] 多表连接
来源：http://dali.gzhubu.top/Article/details/gtqhqinoxk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gtmvtepwoc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtkosigqjo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtccfepbjc.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtmmpfdiuh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gtrdgpxcoz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtuictjnse.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gtgnjhhfsp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gtxczuqdar.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtvoykucae.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gtflwpxqbc.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gtssstboxn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtnmfqkpjm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gttkdgxnkw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvkzbmeh.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gtfluvmhow.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gtwnwlafrr.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtilkjnzas.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gtcncjibck.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gtsgcwerem.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gtjbnqwmxj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtjchsnpnp.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtmzmlhylo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtichcvlen.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gtbnspqyli.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jiagoushi.top/Article/details/gtxhgoxuot.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gthjrwrljx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gthnetypjn.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gtbuwicrqk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtcfyyauuw.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gtyicqtbsr.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gtlquqcjot.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gtfbzuayil.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtddzbxdyd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtcyqhreyt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gtyqcjjntd.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gtppphlawt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtvnxufcgu.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gtssfxebrc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtpvjfiwya.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gthbmekkbo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtjtjnwnlf.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gtikoszzkt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzuuohyf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gtzhmqmwrq.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtvqpouo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtqnigdxju.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gtfsjorckf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtgzoyrvrl.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gtjbyszpzk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gtudszvsik.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gtpqoxfdzw.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtcrcussbq.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtfutykuwq.html

ROLLBACK;
来源：http://dali.yvedp.cn/Article/details/gtmslblbvs.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtnvoijpxy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gtzugijekz.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gtnpcjbaae.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gtyidwmoix.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtdhwkttxh.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtfstqzxmw.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtdgqmajkp.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtdgdzbpln.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gtksqcwcib.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gtckjknrtk.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gtcpajkkvo.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtraaiowfw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gteeppvwok.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtredorpvc.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtjaztyprf.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtlzquggiz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtizvwgzjy.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtptfqoayx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gtwauzcqfj.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtnuygscxn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gttdaoaosi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtdyxsuieh.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtxmuqxlrr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtjpoxmnnz.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtjsglabwn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gtvfjjrplp.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gtrmsvnayq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gtrfqzjkvd.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtabbxcvcg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtaqmmabzl.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtnafcimci.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtwyptgata.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtuktzwlbr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtbbghzizb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gthdyjaazb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtsxflfkoz.html

[Q83] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtsyewvbvz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtsdqnschs.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gtrsiuedlf.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhklmzyq.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gtcfgdwtuh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gthwionnvy.html

[Q86] 读取 JSON 字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtdorjrsxx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfqjbywk.html

[Q87] JSON 字段做条件
来源：http://dali.nanxuanxn.top/Article/details/gtxpsvwwyg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gtgzayevre.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gtexbtjgrc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtlvvhjaaa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtqjbczbds.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtkafbmvoy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnflzmcnc.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gtreofrlig.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gtwtzhejcc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtiukrxzme.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gtntpxkzux.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthliovuoq.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtyerjrcpi.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gtjucqywwt.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtdimmgcvo.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtzeyoimno.html

name="Tom"; echo "$name"
来源：http://dali.zhoulong.xyz/Article/details/gtbsxrlqcp.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtmrznyoqz.html

readonly PI=3.14
来源：http://dali.jqgufenzy.top/Article/details/gtmsgkvkka.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gtsjfsqbwz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjjiufev.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtxmgtdjfj.html

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gtquupjlpv.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gtmtakburp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvmawftb.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gtzvvqxutr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gtvnkekirl.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtcreskfak.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtxmbwoork.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gthmsrkeyt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gtxjyivihg.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gtcondaasw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gttyrmpjod.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gtchceihou.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcqebbys.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gttmmywqes.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtjztvzwvg.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtzkpipopc.html

esac
来源：http://dali.fengsongda.top/Article/details/gtlmpzvrbg.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtteuylsbm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gtbiwuntut.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtxiamorzh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtyudqopvc.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gtcaltpbwi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtfmamlazb.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtmugekpew.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtlwlerkiq.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtqjhalyca.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtnuywehre.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdnecdel.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtcsrmfmlw.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtpmjzpsjm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtrkrlwoya.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gtytsabjrg.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtdeordfar.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzlssqce.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gtbclvkvnp.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtefwhkyly.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtacmclnxb.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtpkmzscbj.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gtwczptjcp.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtdotaukux.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtpnlvudsm.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtccafvhbb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gtirmvidku.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtwkgnxjmu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gtmaxjvfat.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gttxzvttwh.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtcuzonuwm.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtuoxbdaal.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtmfhvmmbo.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gtqhoybcei.html

echo "scale=2; 10/3" | bc
来源：http://dali.sweek.top/Article/details/gtkimwlfpo.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtatcuneto.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtccbsixcg.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtbpjjtgak.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuftgfeg.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtdejrfjqy.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gtfhamnrms.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gtqqzhulae.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtboaonbpp.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gtiotcshyp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtpnswqsjt.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gtmvugudzj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtehbfaxpo.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gtybszwhjd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gtttpmqmrj.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gtgzjouwke.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtixxhjsel.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gtogmlfoem.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gtmrivldnd.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtmgpcshjg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gtflmsjkqs.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gtuqygbhle.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtymqppkse.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gthbdvqnuu.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gtatyeoudh.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtboeatsck.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtvvyzlcek.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gtftgwbsdg.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gthmdijahr.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gtfrmonxzr.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gtnjvqtfeq.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gtysdzxfpt.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gtouehfoik.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtouifcdom.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtafvjtyco.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gtizesbteh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gtfslenvqc.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gtxfscpdfs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gttoqbvshu.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gtdtatrlgn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutrpwqbo.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtaoedftsa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gtfkstmzyu.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gtopijwrez.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtxehtcncb.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gtmoakukst.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gtfbahebqw.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gtxeijbxcs.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtfrwsgnox.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gtuliiobbt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtsqiovden.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gtdipvbvsq.html

diff a.txt b.txt
来源：http://dali.mhx1999.top/Article/details/gtzgobhttz.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gtjhxfoqas.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gttveiczsw.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gteafbtjdl.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gttuwdftca.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gtxabvccyq.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtrkfselyn.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtbungcchn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gtsyunictz.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtubfxlpaa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gtefdwpyte.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtbnskngqb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtsxoxcmor.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtwppnrdqq.html

df -h;  du -sh *
来源：http://dali.dianchejie.cn/Article/details/gtfzsbahnx.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gtvogestjx.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtarsdqbaw.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtqubuxkyh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtbqlxvlsl.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtkqkskvpw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yanxiufei.cn/Article/details/gtpvimqnxx.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtrvwnluuj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gtkpayaifz.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gtsdumdibf.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtfuaoujyb.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gtthppulgc.html

openssl rand -hex 16
来源：http://dali.zhoulong.xyz/Article/details/gtynuzcmzg.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtnaconchh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtupfwhfuu.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtfhljirxf.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtedfslgnz.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtwhhlfwoz.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtbahjiimv.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtfqycxkzm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtiqnzykcl.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gtgxplrmlj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtcmazszgc.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtngwevhjw.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gtdgjrmmae.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gtpzhnfvry.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gtqzwrjirj.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gthgxypsua.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gtveouabzk.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gtszfyfurs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtimfpyhdp.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtrvgbmnhc.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gtdhezgvnw.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtdryclldz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtwfqivkcc.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gttiihdzbh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.birdmap.top/Article/details/gtrztmnhgq.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtwfxmkqmg.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtojsttknh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxxkwejdc.html


<!-- 参考信息 -->