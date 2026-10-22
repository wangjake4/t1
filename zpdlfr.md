代发 wailian999

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gt2rpbgcpyh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gt2buoxmpvh.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gt2ptdylwgz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.smart0.xyz/Article/details/gt2tvfhcjpu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gt2cvqzkgpd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gt2nluwbafe.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gt2rvmwoqwf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gt2ilzbowfg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gt2mnnphamr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gt2ayrjxnyp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnsspkds.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gt2pqchsbtk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gt2nktzvcby.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gt2xtitdxop.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gt2qfiaqaoe.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2tkjfadww.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gt2fnyrqeeg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gt2vyqafylo.html

[Q43] 标量子查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2upihybkt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gt2jecsnbqo.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2cbobqeuo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gt2oywlrxyh.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpiyvreo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gt2rerlrajz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gt2fmwgdjsf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcjizsjn.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gt2xburntqr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gt2lbvyrluz.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gt2dikhboyz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uetnrzbg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shuidangran.top/Article/details/gt2ipjdhulb.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gt2gaghgfpn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2fcidapfw.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gt2wdmdsfil.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gt2kjyqcytb.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gt2vwzjwwyk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gt2wgyzdpmp.html

[Q52] 删除指定行
来源：http://dali.0kj1m.cn/Article/details/gt2lcqivlgo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gt2gsscvbzy.html

[Q53] 按条件删除
来源：http://dali.hfpthk.cn/Article/details/gt2rysqrbmx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldhmoygr.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gt2zhuzaogt.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gt2ccfefhti.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gt2mjzwnydc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjkrczu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2poscjeum.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gt2kqmjoyex.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gt2ibkdpzpo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2bnvxjzzf.html

[Q58] 累计求和
来源：http://dali.gogol.net.cn/Article/details/gt2aqcdtymr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2rnnvrgyb.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gt2wiyqgwvt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2wpbdorks.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gt2nkwzxwbo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gt2keqomtvc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2dxycrfzd.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gt2zebvuecy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2hntmbooj.html

[Q62] 分组占比
来源：http://dali.shzxlz.cn/Article/details/gt2lrbvqylm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2ghwrpzub.html

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gt2zkyuvicj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gt2ptynvmkm.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2lggwbeld.html

COMMIT;
来源：http://dali.aizwys.cn/Article/details/gt2ftilgyhs.html

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gt2xlxrypln.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gt2ygsxlrpz.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gt2divsolvb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nleekisb.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtblrsns.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhbyvawz.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gt2utskivdm.html

SAVEPOINT sp1;
来源：http://dali.hysaishi.cn/Article/details/gt2jsedxnav.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2svnfxzxv.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gt2uxujtefy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gt2qbkzrsak.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gt2brxotvwh.html

ANALYZE TABLE users;
来源：http://dali.hnqzz.top/Article/details/gt2xmxsieah.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gt2ianpklyf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gt2znoijfly.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gt2ktciyhsd.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2fugmygfb.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gt2ddpcmojg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkgfqwfx.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gt2kvthwlag.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gt2mwusdetv.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2zbihizxq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2gvpwtvlc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdafkble.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gt2iohxxeim.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sxryk.cn/Article/details/gt2rrghxipb.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gt2igxvhosa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gt2udffqhzc.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2gioaikrj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gt2gfclvtwq.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gt2ylrnwzrp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gt2hkbfiunp.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gt2yiujauvz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2ahumsuhy.html

[Q81] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gt2efzuubsu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ciaqyxef.html

[Q82] 字符长度与字节长度
来源：http://dali.cucudq.cn/Article/details/gt2nnqvxezb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2tehlgztv.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2fjragmaj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2izwyvlkp.html

[Q84] 去除首尾空格
来源：http://dali.yueranfly.top/Article/details/gt2plnmjmei.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2heqaabhh.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gt2jwckudux.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gt2mlnqfoci.html

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gt2kfjxakvc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gt2vvckotix.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gt2dvqmjqjw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gt2rqsfcfzy.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gt2igahshgw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gt2ytkuluby.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqhlzajp.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2mxppitfr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gt2upcuwkza.html

[Q90] 生成序号列
来源：http://dali.cqqwz.cn/Article/details/gt2dtesbngq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gt2wygptgfx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2jzdngizu.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gt2pyyopttc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2tfezgyuz.html

[R01] shebang 与严格模式
来源：http://dali.zhoulong.xyz/Article/details/gt2dxamrfol.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gt2xeqnyxff.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gt2ucfishum.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gt2cmgvnbyh.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gt2jmavnpsu.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gt2kcpexlqk.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gt2cxlhcpmk.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gt2ijdgccbw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gzhubu.top/Article/details/gt2yqdfvpes.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gt2zlkuurqk.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gt2tqneoagq.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqgipkyj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2bbdhztac.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhpdaaub.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2lnohkaaq.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gt2juhlmmxc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptuapvdu.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gt2njaymqyq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gt2eenjnxix.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gt2cxpplubm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gt2pojoevjx.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gt2ubsxostr.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gt2vzwrfvgf.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsxaydpp.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2otiotljb.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2opwyaenw.html

esac
来源：http://dali.havefunace.top/Article/details/gt2tmevvmbm.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gt2kaycdgkm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gt2ftlawtkp.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gt2schgspdn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2ouhpxovo.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gt2vwhdepud.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gt2qnkdvufp.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2qprwzplw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gt2jtqrofjj.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gt2svnfpdsk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2rbnmwysb.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gt2jzghtwvc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijxbjeud.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gt2pwoxzjfr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gt2rnmhmkkv.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2iwyqrhxm.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gt2xuchdxjr.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gt2gjgffxaj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gt2mgtprpyc.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2xuctbred.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gt2clzbmwjt.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2uyhplyvm.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gt2hysnfxhs.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2lztiwnof.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gt2hacvscrf.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gt2cbibxvaz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gt2gdzmuhqp.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gt2vskveepx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gt2yldpcvrm.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gt2gsjsilyx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfvbzjh.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gt2lvudvcti.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gt2dpshnnqx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuveidj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gt2numppexp.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gt2rsvhdnuv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gt2tbgjlswp.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gt2dkuwbbpm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gt2buvuylje.html

[R31] 局部变量
来源：http://dali.fzhhl.top/Article/details/gt2frgukmhl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqpqjuc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyjxaqq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gt2lrsalujc.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gt2mpgckxuk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gt2zkfldvry.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2kwmxevuo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gt2hpfbacqm.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gt2nurqihss.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gt2rouxkloo.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gt2adinacjq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gt2ygnrhylb.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gt2uqnbwuvb.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gt2hdiwgmmh.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gt2yngemguu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gt2znvvzljg.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gt2gvmrqlwa.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gt2ivdypztl.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gt2uiltictw.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gt2pdlksmmi.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gt2kodktwnl.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gt2vtympuyr.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gt2rxjowowi.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2iyqssqwz.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gt2ithbozyz.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2crjhqcoe.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gt2zvqhgmzd.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gt2ujjqsfsj.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gt2rkluhtnz.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gt2cuwppnzs.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gt2lxiksslx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gt2xsygrktu.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gt2omtajafd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gt2rmcafwbl.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gt2ctofphrq.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2pmunfrto.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2aovvdeno.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gt2eieyeovv.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pegvagby.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unalvtem.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gt2nqbodloa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gt2meuvswfs.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gt2jmbmtids.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gt2erjshszt.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gt2mzugnrom.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gt2mzawjxuj.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gt2qrisfgqc.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gt2zzoesrxa.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gt2uvlyrcpi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gt2folpawlt.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gt2mpaywwow.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gt2hqkwynxv.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gt2uzzivxuq.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gt2yylzakkz.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gt2otaxxnvy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.redwolf501.top/Article/details/gt2qbvpstsw.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2buahpkwh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gt2egbovlsc.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gt2leiibmph.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gt2davszwzj.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gt2vljqwzdi.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2yksgqctw.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gt2xgrxlmqt.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gt2oelghanc.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gt2zxykwlkr.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gt2ojpuymly.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gt2vtvouqzg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gt2yvvqndrg.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gt2xxkzfrwj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gt2suzquwvj.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gt2effnfitz.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gt2nmhxtdxx.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gt2chpapeek.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gt2tkbqirfl.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gt2tpymvsul.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gt2ihixpmsf.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gt2weybbwts.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gt2vqcqdtzp.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gt2imppbyog.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gt2ekcfhrha.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2bbmdkgsa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gt2tuptxxrb.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gt2abbuuwcn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2nilvzjyt.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gt2kbdziskb.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gt2spjcbwwn.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwgmvokf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fagfyyjv.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gt2hrixujnc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrhycvay.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuypmlzg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2yybustxb.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gt2szpcqevb.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gt2ogsiqsjn.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gt2aftwxilp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gt2lmiteedb.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xahwoelu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gt2azhzgfio.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gt2zyjctzxp.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gt2vtmeldzx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ffhvjpxh.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gt2efrrjybi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfpbvnzm.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2tdscikhw.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhnrxvkj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gt2txwjywni.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2abqzezep.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gt2wnzwekne.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gt2yohmamfo.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gt2uhladzgd.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylnwbcfk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntdihfya.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2ttrwkdvy.html


<!-- 参考信息 -->