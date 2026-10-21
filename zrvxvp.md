代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gtqzjlwdzw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gtfywedbmw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtlgbexiiw.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtemyndvcf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtucvfhlxm.html

[Q30] 分组统计
来源：http://dali.c1oappe.top/Article/details/gtrndxwhaf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtheacoglf.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtqgjbihtm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtwguhbasy.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtupfezvsy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtxmxspwhf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gtznblkvaz.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gtfngdcgmp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtokuppsvw.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gtyfmwubaw.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtftmsydkj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gtcmzhkbnq.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtbprwytep.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtvhtqpxat.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttahtrzny.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gthsqooyve.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtzpvdgohp.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtgdyiplbc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gtryxljzni.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gtqrblucsq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtdsfthffw.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gtzrkomlhf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtccscmbya.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gtpprawfor.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxuanxn.top/Article/details/gtnkjloyhj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtotltmvsx.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gtlsvjhyyu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtiahffwdb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtzpexuhkm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtxbcqtgxj.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gttuhnnufp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtokkcyrtd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gtteqoahro.html

[Q43] 标量子查询
来源：http://dali.redwolf501.top/Article/details/gtdpitaxlb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtyalqwjqm.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtzaqjxzov.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtrxnswwef.html

[Q45] EXISTS 判断存在
来源：http://dali.daria6918.cn/Article/details/gtkmrwetiv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtofalurfd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gtswukziox.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtjnnbvwhz.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtwovbabaj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvokfftj.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtiydbpwkt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gtrfckfxec.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.snrcjt.cn/Article/details/gtjhtjyaep.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gtiinidsoz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtwrautfal.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gtowronmxz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtovlpduys.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtskhmohtw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aibaodan.cn/Article/details/gtqsdltwkx.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtvbslfnsq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtkaglkfag.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gtgvmgjlfs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fengsongda.top/Article/details/gtwvctilva.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gtrlagmlta.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gtqlrxvgwq.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtbmiltnmh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtkobualkh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gtbscwvhax.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtmjdxuvxh.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtynawnkrd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtpkawrghm.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gtmlzfaham.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtwliqsnaz.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtomnyprec.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtlolaobdm.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gtgvivvbyy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gtyiqpxpfu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtcgvfmvaf.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gtnvvbdsmg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtvnupneho.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gtfjilkgkv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykrxmvtr.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gtdwaicszx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.9152youxi.cn/Article/details/gtxctswcjj.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gtsdogepch.html

COMMIT;
来源：http://dali.aizwys.cn/Article/details/gtgbuzmmnt.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gtjawlsqzn.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtrumywxbu.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gteaieggxn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gtpjpqjonr.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtwritkiog.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cheryme.top/Article/details/gtraswkgba.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtyxdqnpas.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtgvasmdxf.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtnrcmzixr.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtwoalfuni.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gtutevomod.html

[Q70] 更新统计信息
来源：http://dali.chenjidiqi.icu/Article/details/gtucjzvwif.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gtbaxfohju.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gtyzfwzmxz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gthuzvgnfr.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gtdfbhirni.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtmdnekoit.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gtatmajcbv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gtmhnndekh.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyzeckja.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gtzhgavspc.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtffndswzb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtdzysvkmr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gtfhemkkxh.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gttqjdnttf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gtzibnyxez.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtvfdzzvnm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gtkptsyihw.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtnqmzkvyb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gtrbsexrqi.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtxiixjnvz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gtkkkoeulm.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gtvajurzdg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtjprkikff.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtdjswmspr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gtrczdmsar.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtdarstwhw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtwvraqkdi.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtirzoerjl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtwsvgclvq.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gtggbvfbrp.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtzzgmukju.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtlcnlilpk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gtnzjfrisq.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gtppovdxrb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gtdqsgmcpw.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gtfknosekq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gtmajquejr.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtujnncfmc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sweek.top/Article/details/gtkermzera.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyoyunbtw.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtnowdshvc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gttqafqevu.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gtqextuwmk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hongshengwenyu.top/Article/details/gtdxerkucx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgdiogfnc.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gteojlrhlw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtuijetvmp.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gtjyvrrkft.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtyfvxxwsn.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gtrjosgyma.html

[R02] 变量赋值与使用
来源：http://dali.ydzc1.top/Article/details/gthmebdazz.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtzhmbmmkg.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gtknmnvyqs.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gtezyoinrp.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtlkpubehd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gttplmwesq.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtueeowukv.html

name="${1:-default}"
来源：http://dali.hywenlv.cn/Article/details/gthiaxenep.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtknkzlncm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gtwgjizmdz.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gtngfwckwi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gtpgrragvd.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtxyfhvjhm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gtrmlgfotn.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtktnvfwwz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtbxnplwmr.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gtlikapyne.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gthtdtkzvs.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gtczpxtiai.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtxagkzddx.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gtdjgflpnc.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtwfzgbnnm.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtxjhieyjh.html

esac
来源：http://dali.guannengcc.top/Article/details/gtzqxqvirm.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gttiqchelo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtychqostr.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtqijwcxag.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtcumkstii.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gtteanpotx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtmmborbax.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtjwmleidm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gttpwxzpbv.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gtpumbovhz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtymzdafvs.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gticbdbwjw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gthgpwokhz.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gtavgpfgnv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxytyiqvd.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gttrjjgnic.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gtcumheoex.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gtkeeveitp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtyhoyoqen.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtkgyacnns.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtbjqgdzra.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtxpfypcqy.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gtbsfqensc.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtgwcxsveq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtirliirhw.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtjzusdnhh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtpqdxnyej.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gtapmtqxpt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtipotuahx.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gtdnicawoz.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtlwqniqld.html

[R27] 算术展开
来源：http://dali.sufxvd.cn/Article/details/gtkxdcfsdw.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gthfcagoxt.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gtctzpzwgx.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgufenzy.top/Article/details/gtdpilxjvl.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtxzkytkhs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gtlzcsgqkm.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtoohewvbu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gtsvfdsytl.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtvvgwrphe.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtvcnvtmuw.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtuaioprpx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtnmpjcjhz.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gtuwbjggsg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjilfhqc.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gtjesptorn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtmenkjgyz.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtkgaekpuq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtqnmwrlpr.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gtuhswxtzs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gttrcmowtq.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gtdgnogfpm.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gtxeodumui.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtieakohmz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gttzdefmlt.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtprkrmdsb.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtzqhrwsvz.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gtwlfamhoc.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtjpbfdsuf.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlfcctzj.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtncdbkzaz.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gtqvlnsyhk.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gtucoranmz.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gtdimpzhml.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gtntjrdtjg.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gtoddzwtwo.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gthxnyflxj.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gtwsqxnaap.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwsrtdwp.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gtuccfsxqu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gtnscdcstl.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtjgvhkeyc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtyhbjccph.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gtjxzcvtiy.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmzvdlzf.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gtmnalogsk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztwofncn.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gtklagrwnh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gtlezhdoie.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtgiuwsrva.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gtstkpmhmh.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfkyxtin.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gthcjvsqfz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtmpajrepd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtscnotcze.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtgavvftvj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gtckciwaqq.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtonieqhkp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tianlin.xyz/Article/details/gtwetgfwcb.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gtjxkibryd.html

scp file user@host:/path/
来源：http://dali.xylfe.cn/Article/details/gtejdnzbex.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gtnnzumton.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtrteagzkw.html

[R58] 下载文件
来源：http://dali.xuetiantiany.cn/Article/details/gtxvkwzzpg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gtdzxiomrz.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtpllqeebs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gtxmdxnvfo.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtvvfcoapw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gtcwobloqj.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gthxmofqyq.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gtiezynhch.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrbwvglq.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtcdufbvwj.html

[R63] 内存与进程
来源：http://dali.hfpthk.cn/Article/details/gtlpwhuomx.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtueiacpgu.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gtavatyado.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtytjvsvqg.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gttqluclwr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gtwlpkrvat.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gturanzhdx.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtmvirhwrc.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gtxuzmdyzk.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gtbayqqkpc.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gtyfdevqej.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtsfyrbzyr.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gtpwycrixf.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtacgicifk.html

[R70] 时间戳与互转
来源：http://dali.wangshuangyany.cn/Article/details/gtoqvmgxvn.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gtkkpxvqlu.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtuenhdbyj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtspammzsi.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gtrhkbluhx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtjfzvwlul.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtadrxuwrn.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gtpiosiylq.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtwvjnxgfy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gtslsrxmgl.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtjnaklugl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtqcoubqqb.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gteaizbybd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtrxdfqqxk.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrsjxsht.html


<!-- 参考信息 -->