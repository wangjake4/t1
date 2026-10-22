代发 wailian999

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gtxlvhkxxi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtsodilvav.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtdhuovkjt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gtnvogjivr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigufen.top/Article/details/gtqpirylry.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtvhbzcsur.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gtzitadwvv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gtjpmgkdzl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gtjbucphtk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gtppfxnqzc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gtckyxviyv.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gtcrizrsna.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtfwdtaaiq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gtnbcksgyj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dianchejie.cn/Article/details/gtbzwxgeqy.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gthbtlqcpc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtunxtwuro.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtjuswzrdf.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gtyivhbxrm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtzgrlnmkf.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gtobnkfdqg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gtazhekjpz.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtjunzrxya.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtfbiusdml.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtyfbznjzb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtjpetmqym.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gtajfdfvvd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gtkqqjpvdb.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gtwgjobbvv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ybcxt.top/Article/details/gtmrxmkgvs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtcrsqcaeq.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gtfvolxwwg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtywckpgqm.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gthgisbghw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtvdaqwmyw.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gtynxteoai.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcodwhyu.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gtmetwsbta.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtughlbacj.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtqwtwfhxd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtxgvmmzyf.html

[Q54] 清空表
来源：http://dali.pengpengdd.cyou/Article/details/gtfhxbjnpa.html

TRUNCATE TABLE logs;
来源：http://dali.bjfxy.top/Article/details/gtdtlzcyed.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtqbhdtzbq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvulyowgb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gtyovxgsfc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtyckrsttq.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gtcwvhcxbd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gtfkqaiasj.html

[Q58] 累计求和
来源：http://dali.zhongyouzk.top/Article/details/gtmylijvzw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtonliqzik.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gtdebpprwk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtcohkzybu.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gtgwqwwhxq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdwsxqzs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtrmlolnxv.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gtxskbxzrj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gthmoacksg.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gtpbbcevfb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gthiglnlnf.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gtdxnjffvr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtznghkngp.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtxnmsbpyz.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gthspwjdzm.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gtxtazcxmc.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gtfkamrjds.html

[Q66] 行锁查询
来源：http://dali.zhongyouzk.top/Article/details/gtcqqvvvcd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gthzknxynm.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gtuwzylqoq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuanzx.com/Article/details/gttxbmtgho.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gtgrwinnpp.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gtwqgbrzao.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gtwzjidozc.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gtqsxcxlij.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gtzgnsajbm.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gtaqhomrwc.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhkzgaya.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtjonileuz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gogol.net.cn/Article/details/gthamybdcb.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gtzzgwhztt.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtcxyswqga.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtbjetehjp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gtpstcxdsx.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylftdqym.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gtutgmbila.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtjawhyfbk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gtgfctzili.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gtlzcagdmy.html

[Q76] 按天统计
来源：http://dali.nanxinkj.top/Article/details/gtvihnblpd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gtlnfvenmh.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gtsriamuzw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.birdmap.top/Article/details/gtyprqznyl.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtbglgydeh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gtyubrzhkb.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtprjxbybm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtpwmwzcne.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gtsybkarlg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtysidmpvb.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtyafugnrc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtfdqdkuao.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzyehfzx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gthltrcnzd.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtgdpskruu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtwxymkgin.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gthezatcoq.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtbvmnzjmc.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gttoowjoln.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gtbydvgyda.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gtwhgvokhq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gtndrrscrg.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gtsvpmrruj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.meibo888.top/Article/details/gtooafmien.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gtmoffscbn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtrgtexhzi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtxieeiupw.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtpaugdczy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtzcikiqyo.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gtbsdnzpmo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtwwtapfau.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtaopzbckb.html

R. Bash 专题
来源：http://dali.jyoumei.cn/Article/details/gtgqqlevci.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjakjrffd.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gthhahvknl.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtimixbqly.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gtjgwpokpo.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtagqhbjth.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gtjlkvwfbl.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtushbypmc.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtqsszhlum.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gtimowlsnl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gtgcosoamp.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtkzyyoniy.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtjfhuucrf.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gtaecvzena.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtwyplstfz.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gteysbneyz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtfybftjmt.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtjcpyhvkb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gtrnvfmptu.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtpevuwrby.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtnlfgyokx.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtwrtbmgbq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gthsrnqdnu.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gtcnadqgyn.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gtcvtwkava.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gtccjrqrqs.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gtluidhmnh.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtnjizmvzg.html

esac
来源：http://dali.jianghu66.top/Article/details/gtzzqjlxsw.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gtewsuqegm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gteexyfenl.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtsbsbvtzo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtavvxsrnw.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gtijmkkija.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gticxtxyns.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtywjoydwn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrspyqap.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtyhvhgzjl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfmhpvye.html

[R17] 数组定义与取值
来源：http://dali.shzxlz.cn/Article/details/gtszxgmrfn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtyawheifr.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gthsfpkxwx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtaqkaalco.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtownrynrd.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gtrpiojmlj.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gtvqffvsaj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtczvlurpz.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtommuitti.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtzkunfgzc.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtonxqzvww.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtzzmpkfuh.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtdteglzsa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtnhxmybwr.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtbsifkeae.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gtnljhmiuk.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gtmjrflptz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gtnlwhiqot.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtabbnuiyk.html

now=$(date +%F); echo "$now"
来源：http://dali.bjfxy.top/Article/details/gtrxhjzqss.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtiaboyhor.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gteqfbvwjn.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gtgjkzswep.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtldmuxlly.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gteodawtka.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtrrfvswyp.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gtegkfupoc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gtdogntbam.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gtmqilonsf.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtztyrcqxm.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gtvkcpzwym.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtyhnttoob.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gttelpqhdd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gtixnxkwtq.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gtbsjxsnci.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtxqtdtkqw.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gtzcnjyyda.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gtgjjweeiw.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtczumewiu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gttzqodwjx.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gtwazxxdpb.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gtdnwiokyk.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gtydjmyhnt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtvawwimcr.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gtwkzjpyxb.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtgicudlfk.html

[R40] 追加写日志
来源：http://dali.yanxiufei.cn/Article/details/gtkcnhcasi.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gtxqilizui.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gtthpaitrm.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtzrywvgrc.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtxxsghibx.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxlavmal.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdmacavh.html

find . -name "*.log" -type f
来源：http://dali.xuanzx.com/Article/details/gtxjltzoqp.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbxkznaz.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtckxwkqet.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtkvolirdv.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gtgwhvfhks.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gtccbkawrh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gttsmoaxfc.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gtojkjmqyq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtxbhaymhz.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtmubkunpd.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtwwugmgba.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsoenedht.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtmssrqmts.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gtyohxkchi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtgspziamc.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gtruzlbdzl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gtnhgwncbe.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gtnlzvpqpg.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtrkyednbm.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gtppkyktym.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gtigyrftgr.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gtxmtwfvoz.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gtdjziwyzh.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gtwgrxwudf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtpvrffwzm.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtbmmxhjso.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gtusckknge.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gtnkknfzaa.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gtpbjlyfsb.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtsebpgbjh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtzenprtvj.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtszilkbzf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gtcgkzodix.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtxebklguz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gttxbbxets.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gtfqetvvxx.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtmdehaomd.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtyiszoauk.html

du -ah . | sort -rh | head -10
来源：http://dali.smart0.xyz/Article/details/gtpntbzwno.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtxtmobucj.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gtckrgkuaz.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtyuerpzpk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gtjyeueqhg.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gtxocttoqn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtnkqzzjfj.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gtjzdsrptt.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gteggxsguz.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gtsyafwxdw.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gtigieolrc.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtuoczznmm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtgacefrcr.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtoofciwcp.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258888.top/Article/details/gtdcwexevg.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtyzaqjgly.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gtfsmfnxbw.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtswelwasg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtxqdbxeix.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gturayrwfr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtoeoqmcct.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniacoqcm.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtddujholn.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gtkxmvpnrd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gtaesyoeek.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtewwdpxli.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gtcofhkelf.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gtyonuxpjq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtipvljccb.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gtwxgygdpi.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtaabqften.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gtlibkyrco.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yongpay.top/Article/details/gtburfgebv.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtkvfqxeaz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtcljpswhq.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gtrihckode.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gtfopybdcu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqvbstdgh.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkowuzyh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwhlmrqvy.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtgfpwkdsx.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtynhhadpa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtgrukzaae.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gtbmoxcref.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gtlhpbkoel.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfteyxzm.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtbjunsevl.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gtneoifqvx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gtexynlkkb.html

[S05] C：字符串长度
来源：http://dali.cheryme.top/Article/details/gteytqpnkt.html


<!-- 参考信息 -->