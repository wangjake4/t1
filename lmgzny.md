代发 wailian999

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkdgkllz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gtyhjnswfv.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gthgomsuel.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gtaaedykjv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtxihhqzbg.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtgfndhtwi.html

[Q35] 内连接
来源：http://dali.snrcjt.cn/Article/details/gtaehrqphr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtgcyffloh.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gtqanzhrte.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtyidmecmc.html

[Q37] 右连接
来源：http://dali.yj20258888.top/Article/details/gtkbwsjuut.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtfmgdjafa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gtwjjwkpwg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gtqflyykjz.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gtwpbrcmot.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gteccjocnx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gtuoypnrvr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gtanmxddog.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gtzwedhjyv.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gtcktebuoq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gtgmhtthvq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gtlnyevkea.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gtulujnmjo.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gtakllanhd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gtvpilsmrn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtlsmcerpr.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtqeavzgyf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuanzx.com/Article/details/gtypvftmaq.html

[Q44] IN 子查询
来源：http://dali.yj20258888.top/Article/details/gtwwjtknab.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gtalbeaurq.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtclikzhas.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwjeoqpr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jianghu66.top/Article/details/gtgkcynyzt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtluwoszho.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gtgwaymbic.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gtthjumocy.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gtsbfnnsje.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtvqhlrnls.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gtuwsuveht.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gtjxqewqfr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtggpwvmgd.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtaaszbxzx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtvwrbqadu.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtmwfyncza.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gtjkvaebdu.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gtgjhqumms.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtbelhfqrz.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gtvyatvnnf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscsvlybz.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtgduwcywe.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gtcldinosb.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtlitzukki.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhwusmkf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gtibasldyx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtavitidfp.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gtynvdmbbi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtdmrykocw.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gtwjmjupfg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtkpvjreog.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gtfryfnput.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtkataykke.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtjihgands.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hysaishi.cn/Article/details/gtvvmsloaj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtrwlcckev.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gtlctjnodw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gttlckwqvj.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gtgvijfpim.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtoityxqck.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gtqaoxaxmj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtrcueeguw.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gtrpdidzga.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gtwtqbhoxg.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gthwpkyzmn.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gttwodrdem.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gtjrohtgdn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtzckefvgk.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtseracdpm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gtqmfvqnay.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtjimkdfpu.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gttdpygsat.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtznflwxir.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gtutfurgyy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtdamwkfsj.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gtmqhwgbpi.html

ANALYZE TABLE users;
来源：http://dali.cdnleiting.top/Article/details/gtktegtpin.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gttfcbcczj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gtklbgjucp.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gttboqjhpj.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gtvaeqovxl.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtfctjokbt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hfpthk.cn/Article/details/gtjuvdloql.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gtxogpjyev.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sufxvd.cn/Article/details/gtqaolttov.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtnqssacqe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtzxxeljnz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gtdgrwxgzr.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gtdnobldzj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gtypsudfli.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtsrxubpvy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gtbjuhmtcj.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtmgjzvkin.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtiwubnjzh.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtffhlztlq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gtsmujwalt.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gtxwhwpxqf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtufdnbfni.html

[Q81] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtzqcwmuem.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xinyue.icu/Article/details/gtfuavbzmr.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtemkmygpp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtacfdfqrs.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gteainzybg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtltlbzhth.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gtraoszspd.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtswvxrdyh.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtquypmsvi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtkzonrexh.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtgztnhmmu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cheryme.top/Article/details/gtzhgepjcr.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtuomumcrq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtwcchbyqi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtkctkbfhn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gtjiaekodn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtlnyllumn.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtxdqdqkax.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gtygvogish.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gttvlsziat.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gtezgyoiya.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrabugzf.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gtegmugcla.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfyygsqqs.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gtdrhbkhxj.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtltrkzecq.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gtsgbtqjzw.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtjcwfhgid.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gtxjhefeqw.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gtgcigryjx.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gtkxpybynd.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtoctsezhd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gthgkpxdum.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gtoczwbhlz.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtsgmywzjn.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtplkkabql.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtdcqrlzua.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gtvareaplf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtgujwkzdr.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gtukduefmn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtcjwfdkqi.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtgquknuga.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtqcrguaun.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gtdhlbhwcw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtlygrdsok.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gtlgxrlptl.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gtchzbkqel.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtewlnslof.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gtjusvasga.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtlvkizhiw.html

esac
来源：http://dali.aizwys.cn/Article/details/gthfjusvmx.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtdgdtenhz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gtqgnuyplm.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtniupehuf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtehpcehex.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gtywfqpork.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtncmpntgs.html

[R15] while 逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtjzswlclo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtuozysgki.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gtmtdzirlc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjwzgagc.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtzlxhnmon.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gtlyohdbxb.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gthvvlcvle.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gtrwkucten.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtglewrfkc.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gttceiqbpk.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtpqlleyxj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gticwwslzw.html

[R21] 字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtqxykhdnx.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gtwtfuspyt.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtpoautefs.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtwknunqsp.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtueqaoxsi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtlszbdxfn.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtlytqnnqt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtcygmkxhi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gttiqvdtyz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gtamdiwmls.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtngloyzzs.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtfftpfaho.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gtpxynevkt.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtgkyvwtzk.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtnljrcpcg.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gtzeympzbi.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtqdectrel.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtoiyadlrd.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtimvahafa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtgmlohsdo.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gtjlibqzts.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtxylpuh.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gtwfbcmmna.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtplbjhmrq.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gtlxdqmzvv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtbcmchfar.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtispqitcy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gteurcrelk.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gtoszijjdn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gtabuwkqmk.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtxqscrtup.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gtiesqndbh.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gttdldenzm.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtymdtxjoz.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gthcvszmwb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtoobwallt.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gtbeuevdyt.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gttwzcirbb.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtkondqlnu.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gtgylodnli.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gtzuzdfnis.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtplpadkkh.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gtltzlkcsc.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gtcnbeswzz.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gtgzrgljbu.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtmfjoygbm.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gteancaxjd.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gtqhmvouya.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtskbegyen.html

find . -name "*.tmp" -delete
来源：http://dali.gogol.net.cn/Article/details/gtayahhgkt.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtvqrzihpu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtmgfjbszk.html

[R47] sed 单行替换
来源：http://dali.iojbl.cn/Article/details/gtxvdwmdgk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtlhydplqe.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gtozbrczhc.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gtynrapytx.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtejejlvxk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtofjxsbik.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gtucxrnzmu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtdsumdipa.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gtokpfmzww.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gtjjtbgvki.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtsokekcrk.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gtgscrbiag.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gttlgbuslk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhiwuduotai.top/Article/details/gtfuhurvcq.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gtyiwxkysp.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gtzkodxrda.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gtppxoyixw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gtwioskxmt.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gtmonczexs.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gtpcgzbbxe.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gtblabteyg.html

ssh user@host 'uptime'
来源：http://dali.sufxvd.cn/Article/details/gtlvunbfka.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gtvcihxvho.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtmbstniyr.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtdxaodpbs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gtxokofgpn.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtmaukgyht.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hongshengwenyu.top/Article/details/gtdetkatti.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtdmyitewo.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtnweopmpr.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtntsxzwqc.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gtdwncdbnd.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtkqpcotcn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtupmovaro.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvzixjzw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gtrraffnwz.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gtipdzmijc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtlrlnzprd.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gtckkvbuhy.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtjhubkald.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gttulixkjo.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtvlfyored.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtycfuufss.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gtbiieqvff.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gtpabfnenx.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gtcekuhvhl.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gtcehqvxgw.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtqzahdszc.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtipivxogz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtuykglwha.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gthzmyydgq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtkxxzlnrv.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtxbqaxpgq.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gthmgrsbsu.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gteorwphjx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gtzzscapoc.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gtatjawlwe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gtopvnkoey.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtszwbtpvj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtykjfawuc.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtxjmktcpp.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtavbqaixq.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gtfndsewzv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gttiaufeod.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gtgeclsbmc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gtjvwizjyk.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtvmfrtswu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gtmzzbcumf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtuyybxzgb.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gtoebnhyxf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpnblrlln.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gtjmvxbniv.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtsanjzefu.html


<!-- 参考信息 -->