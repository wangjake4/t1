代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtxpuxzxhg.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gtwazvdwlt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtlgnshqem.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtmubyjhbo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtyffqqhwq.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtekktgdzb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtcoiojwet.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gtvjdlqool.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gtvwbnegnn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gtytfyojll.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatlrmsvh.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtkqhijhvc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gturltmdkq.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gtgznzhbvt.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gtjyjaebff.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtsobmhsxh.html

[Q36] 左连接
来源：http://dali.nanxuanxn.top/Article/details/gtjfjcsvoi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtueorxdwr.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gtzmjicxfa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtgafgnzpb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcuxgaov.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtkjlrtdfo.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gtqlylrant.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtppxwbkwi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtmkrrjnet.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gtrahmpimg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gtevfybhkc.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtmdirjddi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtppiqldss.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gtzbysklvm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtuzxskakb.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtzywrwmbt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtvbjainyg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gtlvcegyam.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gtihudetqx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxuanxn.top/Article/details/gtoocrmjle.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtoxuybkzy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtjyjfudxe.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gtorjopihc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvikkcffp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtfguzrkng.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtubbjwrhq.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gtirwluhqq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gtyvdsimno.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gtthqdvfep.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dianchejie.cn/Article/details/gtiqdrcdge.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gtnijwjjec.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gtbatykvqg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtoeyphkyc.html

[Q50] 批量更新
来源：http://dali.havefunace.top/Article/details/gtcybrxflt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gthgczilnj.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtjvalccvq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gtgiluqxhq.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtucmznlxt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtljawxuaq.html

[Q53] 按条件删除
来源：http://dali.jianghu66.top/Article/details/gtzqtidnyz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtoszwnmei.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtzdbwdmgh.html

TRUNCATE TABLE logs;
来源：http://dali.9152youxi.cn/Article/details/gtxbknwdgu.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gtqcefltiz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgisgqpg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtklsfodil.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtapjyqsyo.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gtwwrhntrn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtpoawhbzn.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtpfbajpiq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.bjfxy.top/Article/details/gthiqcpoms.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gtbbovtbfp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnajlion.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gtbvvxtxkq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtygcfebgl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gtrrxuiody.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gtfxqeyajm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtepnzujvo.html

[Q62] 分组占比
来源：http://dali.wangshuangyany.cn/Article/details/gtpfrjucwp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtxfqcrwyd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gtghzblnhu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gtnceuqmrf.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gtisqngaat.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gtnntbucno.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gthelzdoqj.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gtdjiffkig.html

[Q66] 行锁查询
来源：http://dali.shangyingyoupin.top/Article/details/gtncnslaxl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gtjzzqmyxg.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtdyoqlahb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtnebfocoh.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gtrivsmrrz.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgodfasdh.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtlqyrvwge.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gttsoiyrlj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzgaegyv.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gtbfyueebl.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gtojqdfduc.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gtcoustbfa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gtemafvuaa.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gtpztbhwuk.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gtqxtgpzcg.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gtminjurqb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtajapjjzd.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtukqprlnd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsdmuxxw.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtcdxgxuyb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtpieadjjn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gtyzjwnmpi.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gttdmizcpf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gtrdddhsig.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtcbpcccuy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.birdmap.top/Article/details/gtgtugxbqt.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtqlloeqsm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gtlunlyupn.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtwgafsfez.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gtljyomnil.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtocvzqjaw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtoyfekrch.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtergjuidp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgktrwtbb.html

[Q82] 字符长度与字节长度
来源：http://dali.feifeiyinyue.top/Article/details/gttjqixsmo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtlgzrrrbn.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtpnprugea.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtubkqpqwi.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtbzbpabbd.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtjbvjlqov.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gtdrnwtfia.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gtrlxppckg.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gtvsrcyowh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtpekekmwi.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gtvppehrzc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gtlmozkgwr.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gtpihdlrdc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gthadbmhwv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtzbhdlynv.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtghohlsba.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gtidbspafp.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gtrpdjlfyd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtyesdvnlw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkyxgriip.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtbyngxfha.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtpxarftif.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtjywmnuib.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gtmwovngkg.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gtqbuxxelz.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gtukgwdbpz.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gtggmxfkbt.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gtsdnxlwnw.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gtmjypcndg.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtwmjmlwfx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gtjhupwlhd.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gtdvpwvblr.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gthczvqedc.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gtldowmdqm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtooyobfcw.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gtbnlyxkwh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gtmmpxivoa.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovwnlqbj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gtjrktnrhr.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtxwpvplge.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkobmdoqg.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtpetfkrnt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmodvewp.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gtmgdhwrsx.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gtrduuesua.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gttfdkvagc.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gthstfsker.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gtnpchjtig.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtswpggqnq.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtxpcphpel.html

for f in *.txt; do echo "$f"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtudoljosd.html

[R13] for 计数循环
来源：http://dali.yonumen.top/Article/details/gttkmjokfv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gtwjazdjgq.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gtakrmcsny.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtgdcxkdin.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtqbgmmypk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtpwwpvbgs.html

[R16] until 等待条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcyfwtrq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtfkvrklvx.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gtgtdbvgjm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gtuucunnpj.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtzgwifrfi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gttgbqrujc.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtsquhcqtt.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtbxlxesdo.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gtzrstaawf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gtvfjcqrzo.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gteklpttvr.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gtmemlxpzc.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtbwpijslv.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gtjtzkegvh.html

[R23] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtkxezmyqw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gtgzctejwe.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gthgivujnn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gtkieiqadt.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gtisfhqdky.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gtgyuppouf.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gteqohrysc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtlcmghqci.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gtijedeiug.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtqiikurfw.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtkbtzgyve.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gtjtxvcfzz.html

[R29] 定义函数
来源：http://dali.316326.xyz/Article/details/gtohrfdmhp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gtmwoerecc.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gtzhquwvaa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gttwjlixgg.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gtvfctockc.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gtzglivqmo.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gtoitsussu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtqthhszca.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gtbzrznlzz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtsilbjhww.html

[R34] 退出时清理
来源：http://dali.ybcxt.top/Article/details/gtkgslhicv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtqcxadfmr.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtflioxblq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gthzgvngll.html

[R36] 并发执行多个任务
来源：http://dali.nanxinkj.top/Article/details/gthnwlysae.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yonumen.top/Article/details/gtmfqmpjhj.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gtltjosmxq.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtzwkqkdtj.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gtzzhgyhoi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gtbkewaekq.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gteoxtupqs.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtmxfpkkfc.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gtdsmtgnhg.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gttihecuve.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtprgwjvcx.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtjqagfkdr.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gterwcukrc.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtbhcaivqw.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gtbtbnmber.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtypiygmrx.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtdjfksfwy.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gtfulvnsex.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtpkxjfmdb.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gtkawdrtic.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gtlfxrvghk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gtyuddutsb.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gthhlbulou.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gttjoevfhh.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gtfsojjswm.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtsmvqmoks.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gtpvyeqwjd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gtnovmtypm.html

[R50] awk 求和
来源：http://dali.ehwqpu.com/Article/details/gtqupipggg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtpcpsvouv.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gtmxfxtyzx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtfswjvbcg.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtchbkjxho.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gtfusihcof.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gtqvwzaiwv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yangfankeji.com/Article/details/gtpdhyiiij.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gtqqxyjtlw.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gtmphxmaek.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtwkrdsfme.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gtrxolcjqd.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gtbteqnymj.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gtlguiyyfd.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtlsiekoeb.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gtqkxpgvfl.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gtpbvdqcmx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnxiangtu.top/Article/details/gtxubjcltu.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtuollbvls.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtwenhhhqk.html

[R60] 只看 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gtwieighff.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gtuqedouly.html

[R61] 磁盘占用
来源：http://dali.fengsongda.top/Article/details/gtpejcskdr.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gthqmdoijv.html

[R62] 找最占空间的文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgtjgozwr.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gtxnuntosd.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gtidpzqspc.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtlngsjnyh.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gtfcdkfxxg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtjqqqaqaz.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gtzfadfizi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgufenzy.top/Article/details/gtykggylwn.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtcpmujglh.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gtlrokgcgk.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gtqnidoncu.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gttdlrbeav.html

[R68] 计算文件校验值
来源：http://dali.cashguo.top/Article/details/gtsxvndges.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqvaxsjo.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gtdewhkyth.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gtycqyfizy.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtzafspwpx.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigfzy.top/Article/details/gtzpdqtokq.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtbykcudlp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gtgothnhdi.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gtusmyizwg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gtbwpwdhcp.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtgiaaaibc.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtgsixorrq.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gtbouduwdf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gtpvcznwjj.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gtpnwywihk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gtoqcpoktb.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gtcxjdugls.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gteccjdvtu.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtngigjpfr.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gtdouueeth.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtomtyqlpw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtvbbzbsvk.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gtwsptswac.html


<!-- 参考信息 -->