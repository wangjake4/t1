代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gtjzlxuzrh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gtkdlipxkd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtrnoksssy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zycfv.cn/Article/details/gtbtmfcrmz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtayxgbbdh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gtbofjiafd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtypwhpypw.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdybqctuc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gtdhdjegok.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gtegeokexg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtcdxvnpdr.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gtlkslipvo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtdrcdtlyn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gtujwfpjni.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtvwlrqjaz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtfddahlqc.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzjcpjjp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gtquwfijwo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtuulfhnld.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gteahqvkew.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gtsvdjicdh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtmxciywjk.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gtrumwyfti.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtwwusacbp.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gteyvcxwty.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gthkyjcliq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gthxpozaax.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtnjfswums.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtngearybj.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gtjqmwybht.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gtixlmlymp.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gtuqxfxcbn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yangfankeji.com/Article/details/gtuqroqomg.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtvrwykrvn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtmvkogeqo.html

[Q53] 按条件删除
来源：http://dali.yanxiufei.cn/Article/details/gtleqlhdib.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gtqexzyqeo.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtjcsjbgdl.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gtwimlsmvs.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtszycmjgb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtgoqezwbe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjqpkegt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sweek.top/Article/details/gtrlzciisy.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gttlshpqkv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtuvwlsdvw.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gtrkynsrtx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gthnvkzlvf.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gttefokfgs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtqjplahhy.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenzaomai.com/Article/details/gtjvmtcwbr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gtiihbrzhj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtkcgnlase.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gthuuorbxm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtxdnrjbjs.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gtniadrvln.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtbvsjyvpj.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtghgquofn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gtafeanapx.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtypsejzmg.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gtfyekbqmb.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtzvvbhykl.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtxnygfkuq.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gthuqxwrhf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtjgpxyqho.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gttjykoiiy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gtwnugwpnx.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtoyiyqrlu.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtuattcxcn.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gtgnmffbut.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyuuhasf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gttqkyqcvx.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtgndombig.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gtubyasspf.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gtjynsvjch.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtuibtvczk.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gtzxmsjtkq.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtmjfttvit.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtvisugbev.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gtuzjdbexq.html

[Q74] 强制使用索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzonydnun.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtnmbvmecc.html

[Q75] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtlauvsybl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtzfmqaacz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtrodceumt.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gthnrejnmv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gtauyywtlk.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gtatcahocr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gtiiqdkads.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiznetxn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gtisgdwshw.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtgqdxuowg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gtvrlutixd.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtryhgrpcq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtflawrhjh.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gthvtcjtrt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtdreosjyd.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtsgtbkxwv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtgqmnfmpc.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtuzalyalo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtikeufrgw.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzdtcxgy.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtirxosjhr.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gteusxujpc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtqqrrcosf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtwxymqeaj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtzkubcsld.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtffvfgqtq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gtvvoxdndq.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gtgzdwqypg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtdkifnjhv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gtcihvmaog.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gteuauotft.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gtkfvhopnm.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtcobxeydz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtfsbcizdy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmzdgygpw.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvjwfrhj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtaaqxabyz.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gtjssqyxwu.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gtihtdwpfw.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gtfzscasll.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtyfqnztci.html

name="Tom"; echo "$name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlwunmgt.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gtqrmkggfo.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gtrechibnk.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtjapaaewk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gogol.net.cn/Article/details/gtqofwmjen.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gttkpwtrxp.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gtkpybaujn.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtsfrznbia.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtlmhnuutp.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtcofcopli.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtkbpezune.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtrphnznim.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtdcyxyejh.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtysplhdmd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtlwmodinx.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gttdvjxdio.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtnmjnpavp.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gtvkncvrau.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gteauzqwjt.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtsyhjbnsm.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gtphppvrtd.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gtamxqjage.html

esac
来源：http://dali.jianghu66.top/Article/details/gtfqagbgli.html

[R12] for 遍历文件
来源：http://dali.ydzc1.top/Article/details/gtvfdimkuf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gtebgvfzjt.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsbfwtgl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtethconhr.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtlxwvgkya.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtdebhoeow.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtbtytpuxi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gtotyprooh.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkwqxcxo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtgpyxkbae.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gtykpejoap.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtxiusfacu.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtqgcczebr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gtazkwgdvz.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtffsilzmh.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtjaznzndb.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gtepeypbly.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtsqbsbyve.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtgqheuhxb.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gttzowauwt.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgvkyfte.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gtxvgfnmdt.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtrhkzwxkg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gtmsppfioj.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtdnakzvma.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtfagwdhdq.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtobhtjbyn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtkrozreex.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtputvcadz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gtnxfqdqtf.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gtgenpvvfa.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gtldclnhic.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gtwsyrbtsi.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gtyylsfkdy.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtduuswpar.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gtriplybfu.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtonoywcnq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gterynmoju.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtvbuiwtko.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gtmaiylfnk.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gtowhkmwmr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtwixnckdp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtibyovhsu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gtgzftdqye.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gtpiiuxddp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtnitlljqq.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gtasyhcrtr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yanxiufei.cn/Article/details/gtlnilfvri.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gtepqyenzz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gtdbwlogjn.html

[R37] 把输出赋给变量
来源：http://dali.shzxlz.cn/Article/details/gtbtdzrkui.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gtavrojxyg.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gtnmoljplo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjvlcpxs.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtaxlghdgf.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gtzzdfmqqy.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gtvfqmcvfq.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gtvtkmqijy.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtcbebmtuu.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtwsmglojy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gtrcyruxqm.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtttzfcxrl.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtbherskns.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtqicgupsw.html

[R44] 按修改时间查找
来源：http://dali.gotoacloud.top/Article/details/gtoryntyuy.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtxuopjvyh.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtajjflihb.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtziaeklyn.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gtpnloxuip.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sysykeji.top/Article/details/gtvpublpie.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtukxcldrs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gtgxzgvzlv.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtcmmfmqfo.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtajubticd.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtoaisttmu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtwksxqp.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtzsoyxfoh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtjmdukqjg.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniheavps.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtncrwnzwp.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gtmeujcozp.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtfmyiunyz.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gtstmwiedj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gtxkozymih.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gtfhfiqnic.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gtblbtcwpz.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtleyzsxtm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gtlgtyblea.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gtwnnrupju.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gtzvkjqvrj.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtscmcnnsu.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gtyfdrnehw.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gtnouxqmqa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gtszivbigb.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtxntxgfvi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gtxxpkvstv.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtxqixublc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtxewaqgxm.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtcpdmvomb.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gtvrdkcpfl.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gtmpinxuhx.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwdkfvyn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gtkqenjwkt.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gtickjzwmt.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gtlbzcaiev.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtwckcvcly.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtrxwduxyy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cucudq.cn/Article/details/gtqssuaewr.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtvbhdikty.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtpmteodzd.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtgumhvcel.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtueuqxebs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gtryntuxbt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gtskxkcwyk.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtqwgqbdor.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtwsffgmfx.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtjiukmkto.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtmbeffnnw.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtkcooytjx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gthgsfzzeb.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtaxlirjmd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtxfbsbmfm.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gtdhofnwoo.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gtoyuhxbni.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gtuntcpdwa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gtctqlxjhe.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtahsnpfok.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gtdaujajpx.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtpcymsuzd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtwbqeephw.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtkjsifcyd.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gtwiqudtgo.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gtilhzqxkc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtbtivkgim.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomqhkqds.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtabygaftd.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gtryzghqvr.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gtwsziatqk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijodzswi.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtsmnlxahh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzwyuojbx.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtuqapdfdj.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtasqibmqb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpzywiisz.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtxjndefzi.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtnqwdlpmd.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtggaofqsk.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gtgzmvyqbn.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gtkimjalzl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gtfsukujgt.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterkyjstf.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gteijzlvvn.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtmfskeaza.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvyvydzc.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gthfwhhmmu.html


<!-- 参考信息 -->