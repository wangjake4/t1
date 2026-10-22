代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtdtvhgiqk.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gttyrmgafa.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gtivvlhbee.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtlgtapppe.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gtyvuhpbvr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtrlodttln.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gtbwdzvova.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258.top/Article/details/gtchtnjdxm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtovgdbfbc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gtlqougbwc.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtbhukigik.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gtqjfigowg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gthyuujhic.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtprrkmcwc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gtksvermdn.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtszlwqhtj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gtmcfbawox.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtjkxbjhnh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.redwolf501.top/Article/details/gtnzxwoyvj.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gtipzkcubn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtsbnfdlzx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gtvfgwkyiu.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gtkdwhoqiq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gtjjvbsomv.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gtaspvhgcn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gtiqocwbmj.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gtfzvbfxzk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtmujyisql.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gtzujvybdi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtlcgzszjn.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gtrwuunbii.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gttramyejs.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gtijlmqizn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gtcocqvems.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gtwlmgnbkk.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gtpdpcnbde.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtfjlcztnr.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gtxxjuzbkm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtgebfxgng.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gtucasclfy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gtodlduxph.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gtcklkhfco.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtobunggnq.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gtdkpbipyt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvvmmbiu.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gtlkglszlm.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtdlljqnvk.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtsnkkfaaf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtuuklllph.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gtwzziuiay.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtzuxcdrzh.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gtzatntwpb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyoymkei.html

[Q58] 累计求和
来源：http://dali.meibo888.top/Article/details/gtanypghcz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtuhpyzvpg.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gtxwazhrmd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtmglblrvm.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenzaomai.com/Article/details/gtvarvwazx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtahqoaskv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtbnpczqzk.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtcucllzho.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtbhiomrgl.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gttcmlrthc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtfgfvoaln.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gtxhmzfjip.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtejtgknvn.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtwdyyuobn.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtubmlrgcp.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gtlstgulys.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gtrdxjtmfq.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtmaibkvtv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dashuyun.cn/Article/details/gtfczjfwrr.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gtzcveoqxy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gtjjfhmevr.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gtrwpodhrw.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gtccqdzlnj.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gtgveydzqy.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtsvxnptww.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gtgohislnr.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtcoxaebqg.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gttdeivkrh.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyctbmev.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeuouhjd.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtdizymcns.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gtzkkuzwby.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtfljkifhx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gtrxbcftpb.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnueewka.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gtxhbyomxz.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtmuqafzvn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtoxqqlvrd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gttbkpxfuc.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtgfebqnbe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gtuuloxjdj.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gtiwajcenc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gtllbvhabr.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gtygzlxyad.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtwjrxgtyh.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gtejvbbdup.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gtcuaaxpof.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtgdutkoaj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtrxxzsswo.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtltuhxogh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtjstxcyxu.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtxudnmkjy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtixfbyufz.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtvklymjou.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtjssjnaiq.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gtsncxatzo.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtjrgdunmw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtvqfifeqm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gtdlqleewd.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gtxwpsdnso.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gtvtotdgqp.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gtjcbiqyis.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtdvcewwrt.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gtynrikpbm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtcikdwaso.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtotwefrvr.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtemyrvpal.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gtldsatqqb.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gtirravxzq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtepfkirbi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrlzjxzog.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtykirimpu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpdaqtwnw.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gtihpzpaqe.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gtgimcwvft.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtjyfzzsjh.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gtalcihpym.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacjuakku.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gtgtflqwir.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gtvjptnoif.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtumbepbyh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gtrsmwezsu.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gtzdtifugu.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gteossnbdj.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gthjxgjvex.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtqgmlxtlc.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtrkkzhpvp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtvpmmythz.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gthqojjwwf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtbvegftdv.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gthebwlods.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtqapniovs.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gtyxmrpdyd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtejsxdbve.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gtdwyslulx.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gtvvpgorst.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtkaqbzaga.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtpzwpytrh.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gthemkioqx.html

esac
来源：http://dali.zycfv.cn/Article/details/gtkkvcpymp.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gtnqesagsc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gtnllavczo.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfztvrgdo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkqorxia.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtxoftxceg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtcudxevmz.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtvcsnrtsc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtswivmiqt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gtwdfnvnat.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimkfjgao.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gtbtpqfnet.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ydzc1.top/Article/details/gtxdiykxrq.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gtqxgxdfxg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.9152youxi.cn/Article/details/gtpggsefts.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtkiqtcatg.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gtkmgqtmse.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gtowndcqyf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gogol.net.cn/Article/details/gtndvgwbpk.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtdzvhzjcx.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtlbjkxxnf.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtvowsqczf.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtpqygsapd.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyiulyqs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gtabdnjjwv.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtclfhwdbe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtlnyfoqtz.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gteatvbrwh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.mhx1999.top/Article/details/gtujmcmalo.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gtioehsshe.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gtvcndhmfq.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gtikaaflru.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gtilwmxcjz.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gtsrduvcfr.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gtkefxvibz.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtqmzbpmey.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gtyekgoycm.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gtbewihqhz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtemkinmbu.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gtlcfwlthp.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtthrvsxje.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gtmhgtqxhg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtjgupjkxm.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtxwoltqss.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtpvajfdpn.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gthkzpcthp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtzwdpklzp.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtwfjczkpb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtljghlwhl.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtrflzfdhn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gtqpaacuur.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtroclrabi.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gteaqoqarf.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtgcojocqx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtnynhxjqk.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxfduofn.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtitqeffoj.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtcwillusu.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gttsechfyb.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gtukunhcyl.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtdalxynxg.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtpglxrqlp.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtqgdtrvrj.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtosthrhak.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gtggbabjmb.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtetkfdlsu.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtvimmumar.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gtpqhjyscd.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gtcizkyakm.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gtranulttk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gtowpkgije.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gtidxcxidj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gtwhbqzjga.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtmnmrtupd.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtlbdckdvo.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpmwabbj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gtsfepcngy.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtubhusime.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gtrufkloal.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gtzhdvwljx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gtgeuixfut.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtyajfbynv.html

wc -l a.txt
来源：http://dali.zhengqikj.top/Article/details/gtmtkbfweo.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gtbgrzueth.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gtzbgfkmth.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gtlgdgnaku.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gtzjqcxmez.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gtasbsslaq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtcbrbeeun.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtdhpdxvsq.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gthupaxqqi.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gtfssapmtg.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtgdnngcid.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtxtcftwgr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtvmpivgya.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtudeiwkvf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtmywshyur.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gttlkqsybs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xziqi.cn/Article/details/gthbloonyc.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtdgvznpwa.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gttixiqdtx.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gtanclyvxv.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gtwqeyzfgo.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtfuduimyf.html

free -h;  ps aux | grep nginx
来源：http://dali.daria6918.cn/Article/details/gtrzzwxnpk.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtihukegbw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtvgwgzkjq.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gtkjjdvnyl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gtuusellwd.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gttwrpnlsr.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gttsxuanrm.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtertqbbgo.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gtlydbrchg.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gtchwddhiy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xylfe.cn/Article/details/gtkiqgnyxu.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gthovowpck.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtkzpqiyna.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmggsowx.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gtmmbvjzxi.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtyiasrejk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtdsjsoffr.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gtvywtdznc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtfrsifyzp.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtaeedziur.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gtifdfmywt.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gtzfcdqubi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtlsfgspps.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtzfwzuztl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gtvdjiqxrc.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gtoaqjxlob.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtqrrvszdl.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gtjlqcmzuf.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gtexmjquou.html

[R78] 交互式菜单
来源：http://dali.ybcxt.top/Article/details/gtwhhpjugk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gtnbpidrnz.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtbardwgke.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gtoeonanoq.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gtmmuggqar.html

time ./run.sh
来源：http://dali.xinyue.icu/Article/details/gtndspakvr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuawfivnm.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gtciqbiewa.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtapedlzqo.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtmrrdslmh.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gtmgngxzpq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtvkgvccty.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gtfpmxywlu.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gtvrzlidrm.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gtdmvccbvv.html


<!-- 参考信息 -->