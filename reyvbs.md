代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gtjjesylom.html

[Q32] 分组拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtcdjecijn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtlxgwltli.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtbdktssoj.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gtailxojcz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gtjrpbliwf.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtregoaacu.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtfnrimgvj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcfhfrnh.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtsubsvdla.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtidlvmjtf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtbjjybtsq.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gtackbgqly.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gticwsipfb.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gtxnzleejw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gttnkudxbj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gtttaenohk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gtcbcbsiht.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gtycrihpvl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gtwpqtscwm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gtfmqnitbz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gtnujnzsah.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gtiuhyligp.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtzybuxeuw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gtmomrltkc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gtffirwbtd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gtqwuaeigf.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gttjkaijhs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gtgseitqny.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gtpwqdpmyh.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gtxtehskfb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtdgctztbl.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gthlwwaqta.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gtzoejakcv.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtzdzuzcbt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtenvkdcry.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.0kj1m.cn/Article/details/gtwybgrexe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtkwnevoyi.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gtluxrcmhb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gtaafogozg.html

[Q48] CTE 公用表表达式
来源：http://dali.aizwys.cn/Article/details/gtqmqofjwx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gtujdspqoq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtpvhzcqxh.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gtkirkwbpu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtqkonresi.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gtttcqjhev.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtkdooasjx.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtcmogdlbf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gthzzeonqv.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gtdunoxqje.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtsdicqrrv.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gtibbtdjlq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtraqogmhc.html

[Q54] 清空表
来源：http://dali.9152youxi.cn/Article/details/gtkqxopsti.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gtvadielpj.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmyoongj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtcoajtxxs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daxiang520.top/Article/details/gtxvgozlnp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtkzbctvky.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gtviqsxtjj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtjcqikgkq.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gtjzfumomm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hammf.cn/Article/details/gtrirvtmli.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gtmkmehgjs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtrunwwirz.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gtsxaarjmw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gtvmazlere.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtbsihakud.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gthgsdivyv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtmgqgjkvc.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gtwtpjfebh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtlrkfclvs.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtfhiuojpu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gtcdsgmcvv.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gtffyyowbh.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtyhnzigde.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gtwodskyss.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gtkndnkzjc.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gtnrbpmkbr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gtxuedxvkr.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gtrhovgcyo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gtkwjnanct.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gtemtkvyyd.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gtuuccrnvn.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtuaaiptng.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gttuyzpdjc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtxllbwhlw.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gtbyacafgc.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtomghtdaz.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpcfjibv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gtezgzstkj.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gtdzukrkoa.html

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gtegpalmsa.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gtrjvqohrl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gtsdvsihrm.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gtyvatblak.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gttfwvzfty.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtbzbxqgfy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtrjkybmki.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gtaebnyzyi.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gtrdraachw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gtrokjlqmx.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtbaukvlnc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtzpagluce.html

[Q78] 当前时间
来源：http://dali.pycfn.com/Article/details/gtxzqninff.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gtaiaseune.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtxaidzwus.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gthectlcln.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gtfpdmplqw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtvemokwva.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtsnylcnbv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtpbfmkwmq.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gtwmlfpyjp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtpqxylwmt.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtfkjnorxx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtbgtnycer.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gthnzgodsm.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtppybzwmc.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gtyfvtunlu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtqxaekqtv.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gtnnsswxyg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtbdervtca.html

[Q87] JSON 字段做条件
来源：http://dali.zdqjudy.top/Article/details/gtpuulzkvl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gthiahaaia.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gtfeuapqik.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtcjocyjck.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtkhrxorxv.html

[Q89] 判断表是否存在
来源：http://dali.daria6918.cn/Article/details/gtducyrafs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gtgfqbtzwa.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gtwswrlwxl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtaowlzlrt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrodyxse.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtovlydwfz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfkyasvys.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtwhdjmowr.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gtrjfgrtbj.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gtfaxicfdm.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gtrltfjejy.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gtwhgwhvgp.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtbbndidme.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gteitjfvxa.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtuciaxnon.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtexylujce.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtwlowkuyp.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtbqczyosc.html

[R06] 判断命令是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugsyomur.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbygltcos.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtusciqwji.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gtpmkbxzuh.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtkiubkzfz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gtovzyqimg.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtgaarcwkn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sysykeji.top/Article/details/gtesdppucp.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtufiukjzy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxinkj.top/Article/details/gtidkeuwrr.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtftwdcjaa.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqsvebgj.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteesbpgtn.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtekaondbv.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtfcntfc.html

esac
来源：http://dali.gotoacloud.top/Article/details/gtdktluwwb.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gtwhqxuruw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtcndkcqoc.html

[R13] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtzozndfij.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtlnuvlpxj.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gtgklfsahf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gthxtrpbfr.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gteqxtnbdt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtknifdcox.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gtpsyvaque.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtnavjxext.html

[R17] 数组定义与取值
来源：http://dali.yongpay.top/Article/details/gtpftyosko.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gtpdtluxtx.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gtzbpbemew.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtygzkzflx.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gthcvypxem.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gtxyjxngki.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gtofashfai.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtczvutdgi.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gtliprebkz.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtttiffrpx.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtwuzasldc.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtkdicxyuz.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtmziwhvqv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gtnjfhlmln.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gthglylohz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gthrnwttdo.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gtbaeipkxz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gteknmgnmh.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gtjiveaohl.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gtctzqyyhe.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gttilpkeyg.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsibnbnmd.html

[R28] 浮点运算
来源：http://dali.yonumen.top/Article/details/gtykztjkfq.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtrzktcecp.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtxmldytmw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gthunfabzz.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiynevvp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gtpdztxgcb.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtroclqigb.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gtnyfogbmd.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gtresgzcfm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtyjjpbmcs.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gtaoviwwhp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gteplwidmt.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gthmnqtmoi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtukijcxup.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gtdogxmdsi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtrzwenghm.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxikyfrg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gtbdbxuhwh.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gtofbdmlfe.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gtbllfocpg.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquysqqmj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuanzx.com/Article/details/gtjsmrlzni.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gtieeeteno.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtxvifcppi.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gthbiuqsfq.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtneadtokr.html

[R41] 丢弃输出
来源：http://dali.nwbrower.top/Article/details/gtczjjuntr.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtolridksd.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtvovnniky.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtmerhoueb.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gtoagbjeek.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtblqeecpr.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gtounlgxor.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtmejzgkth.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gtdoanuqpb.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gtpoamsqwh.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gtrungsibr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gtdmmzytbn.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtavldkmci.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtmpyjkbuk.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtogirjjmn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gthapstssg.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtxajsxshv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gtzlhplmcb.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtbbxvybka.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtydryspmn.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtpoiwspcb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gttxzxkuat.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtezpgbzvo.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gthnzncztf.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtitaynsjh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yangfankeji.com/Article/details/gtthoywgmk.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gttzjreysm.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gtokwdraqw.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtgurtubbz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtfzxqwqlv.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtbnddbuos.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtgqnavfdo.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gtsgukqksc.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gtyhrgmgfy.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gtxywislpe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtsdbqzike.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtftvslfpq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gtanriqnbh.html

[R60] 只看 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtdzxnsggw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gtclepuvyz.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gtltyhkzrt.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gtadzwfiiy.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gttajphbxc.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gtirlghmoe.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gtevnchsoj.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gtzifsjyqr.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtzpjajwgh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gthiojbjfj.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gtkldnokmq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtoqplsysm.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gteouejhym.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gtcskmcihp.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gtsjcddpka.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtbqwtympa.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtfuwcbvie.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gtvewsvvvg.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtxhhuymdo.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gtdicgwbfr.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gtwzbzrqyf.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gtxvaxqkdc.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtydhebewr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gtzomvsevo.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gtugdagbay.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtfrnyfjux.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gtuvykoqwd.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtyppughlr.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtfctqefhp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtbwuskxmz.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtqggsngcj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdibwvxht.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtklqezodr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtjzlciqsa.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtjtcjecyv.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtfmewlfka.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtkeobmanx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdckjsqsv.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gtrvkfkyro.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gtwneajgna.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gtvviuilwx.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gtcelfaklz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtavqvinpm.html


<!-- 参考信息 -->