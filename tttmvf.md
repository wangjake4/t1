代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gt2mlfgykdx.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gt2qdyjvdsg.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gt2yztgnvtw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nellqopl.html

[Q36] 左连接
来源：http://dali.316326.xyz/Article/details/gt2vutjxlfp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2oeivxfdd.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gt2hvntqdro.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gt2etnsemxw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gt2qszhahgn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gt2maleolwv.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gt2kfovrxgt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gt2wzvqylmc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gt2tcfwuuue.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gt2diktgjod.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gt2uaiabcwm.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gt2heqhljva.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxvzzshz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gt2oekqcpdw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gt2cqpkkqaz.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2yimkpjlv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gt2uhkksijw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqlidnlv.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2lqgqcpzo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gt2dbavaflt.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gt2zdzimqnr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.redwolf501.top/Article/details/gt2sacxwvzx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gt2nsoidhay.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gt2hcqbrcit.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gt2vfehgycr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gt2mqettxqt.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2huobblma.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gt2emefowgz.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gt2gblxfhws.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gt2oeffdctj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gt2ghyribyq.html

[Q49] 更新单行
来源：http://dali.jqgufenzy.top/Article/details/gt2fhahkzfh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2hrzddbcp.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gt2aetvjnma.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gt2tbyywcxq.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prjllfzd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2dmfmyapb.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbsgtfxw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwfvorda.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gt2qhcwfgzz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gt2mruqydzh.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gt2xugviijc.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gt2viljfxfz.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gt2uufuotue.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyqxymdu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gt2mshzxyed.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bosmqjrh.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gt2bdvrtnnc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2xcrggrtl.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gt2ctneqiag.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2jyzilfkf.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gt2eamlzpyw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2kmvutqsa.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gt2xirsckyz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lknhqtff.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2zqxoyprj.html

[Q61] 移动平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmkrysfx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2oddhzldj.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfhjxsmn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2zfcoajrb.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gt2swsviruo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyhndda.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gt2ucxnqenh.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gt2vfaoatqp.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gt2otmgqfkq.html

ROLLBACK;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igpcbqfl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dimngdir.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gt2gnyznjvc.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gt2jayxhvjg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gt2khsxhwgb.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gt2kgcuyavk.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gt2wsrxhndk.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2usnktyao.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gt2kewrhqcj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gt2pkelcgrc.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gt2qvhglier.html

ANALYZE TABLE users;
来源：http://dali.hnqzz.top/Article/details/gt2lscmgnyj.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gt2ebrvyvmb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gt2okgqixqv.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gt2rfxgqgpd.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjoagtiu.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gt2chymmgwq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gt2azksiskj.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gt2yckglwvk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsishzrf.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2zvwcmcpq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2qjyoifck.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gt2ftftjuwx.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gt2expuwfbb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gt2upfegseq.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gt2jghcupql.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlgddcnw.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2ljwhothq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gt2kbpoavbo.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2nsccftvb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gt2coqtmhlc.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gt2mdpifxjp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnaijen.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhyimusr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2kstiwxxq.html

[Q82] 字符长度与字节长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2oezbglxj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2stfvjbol.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2ybrjnpwm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2utvelxcu.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gt2mqevgfsk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgaehdfw.html

[Q85] 数值取整
来源：http://dali.fengsongda.top/Article/details/gt2tkjqqfba.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gt2eibqkntt.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgwvfkym.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2saqtuvrb.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gt2cukowhbe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gt2sivpnrim.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gt2gounebwa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gt2qbqphlel.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2icwfafpu.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gt2cyunquoc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gt2uqirfcds.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2woqpitbp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gt2kowoaexg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2atzioxgv.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gt2pgphljrs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2eypspnha.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gt2oyqocshi.html

#!/usr/bin/env bash
来源：http://dali.yj20258888.top/Article/details/gt2kmqyiduu.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajifkkvd.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2wgxfvjpd.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gt2vgqrazpu.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gt2ruhbedxz.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gt2sxybjmpl.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gt2zqmztjpi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gt2bbpwcibi.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gt2loukhdbd.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gt2vnjlnxem.html

[R06] 判断命令是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpouqtvc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gt2vtaesdac.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmcgslbg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2hvbyqacx.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gt2jbftsfxz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gt2eldmlacz.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gt2rqowxlch.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gt2kxjjggkf.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gt2jqmbiorh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2vydlymjv.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gt2ximqitez.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gt2vghcqxbs.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qkuhajko.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2lfgvqcvp.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2tqnifogr.html

esac
来源：http://dali.jiagoushi.top/Article/details/gt2vgjllqxw.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkcsuttf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gt2lbdnjulr.html

[R13] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gt2ngfwjqmc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gt2gqncjqde.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gt2cumvymqo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gt2czxcvszj.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2yblmedal.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbasuruy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dthtkory.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gt2nnnuunzb.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gt2rwgpptzn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhengqikj.top/Article/details/gt2vyhyylvk.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gt2codnsyhh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hywenlv.cn/Article/details/gt2gidkrffq.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gt2jfcupjeo.html

echo "${#arr[@]}"
来源：http://dali.sxryk.cn/Article/details/gt2fqssovrw.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gt2ozeolaox.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gt2dsvrkjuu.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2mspcowjl.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gt2jpjamviy.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2yvjwnajn.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gt2hwwcmusn.html

[R23] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebtjuafo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gt2yuzlxjtw.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gt2jitshtir.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gt2mlvkreno.html

[R25] 去后缀 / 去前缀
来源：http://dali.hfpthk.cn/Article/details/gt2orzkeikj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gt2puxbdjal.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gt2kwdawokg.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gt2dyrqvvsq.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gt2aehvtswk.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gt2uiykjekz.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gt2zmlpyboi.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gt2stjvfplc.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gt2etuoslwf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gt2wysknsqy.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gt2cksiobis.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zycfv.cn/Article/details/gt2syjsomaj.html

[R31] 局部变量
来源：http://dali.zdqjudy.top/Article/details/gt2vmdjfudq.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gt2fuogdkay.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gt2kqlmsbey.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kjneysnm.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gt2gnzoapoz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2zarppfnm.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gt2lequxrqp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtrpzyrm.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gt2ynhphxus.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gt2wfhczjtz.html

[R36] 并发执行多个任务
来源：http://dali.316326.xyz/Article/details/gt2ouuigvky.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gt2fdspyhns.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gt2myabmssv.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gt2zgfafcdj.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gt2kfdizurk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytkwawni.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gt2pfqujdfd.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gt2mkektnwr.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kvmspeza.html

echo "log" >> out.log
来源：http://dali.aizwys.cn/Article/details/gt2khmmiudk.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gt2vdxrdquz.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gt2hjtznhxj.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gt2vsqljase.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwwwaxed.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gt2xftzowec.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gt2wyfhtkrc.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gt2hcgejefv.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gt2yxwxqdji.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gt2lusxjrbz.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gt2gyrkjvnq.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwdpljcn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gt2cwatjpjs.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gt2kxdggtcv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2vmbzoyzz.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gt2hdexgzet.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcfixguq.html

[R49] awk 带条件
来源：http://dali.hysaishi.cn/Article/details/gt2fetgaypc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gt2omnnctmm.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gt2ubjnvldh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2otrcalxk.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gt2pvvtoqoz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gt2nljjohht.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gt2pgwairog.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2aegkllrq.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gt2jywatisj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gefjqfwz.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gt2oairdofw.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2jykggrog.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gt2vpvxbqee.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gt2wzlrqvpi.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bitmwdxp.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2arqldmhl.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gt2qolinbqg.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gt2tjjiuwij.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gt2gsoxxqdd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gt2clwjwtlu.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2qyqvezwg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gt2qfsnhdtp.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2jgbbztqs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gt2yflboqzy.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gt2bbjpcnzr.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gt2hkstdcqy.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gt2akmvlvpb.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gt2nsocqcyn.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsboedmd.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gt2yonjgfut.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gt2xrtxxryt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gt2einjgtis.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gt2disfhsxu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gt2qjthjxaf.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gt2todinsdq.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gt2vglgxrzw.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhdprflx.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gt2tpphjhga.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gt2swiikbhm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2tszmjhws.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gt2yrxizkct.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gt2lfpwbapl.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gt2cbeaqbnf.html

date +%s;  date -d @1700000000
来源：http://dali.jiagoushi.top/Article/details/gt2youcrkkv.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gt2qtvuqgva.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gt2bvqkfzel.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gt2qmsxrerw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpvqqhnm.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gt2dhyrvvzt.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gt2emdcahad.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gt2hnnwiaqa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gt2dajedvdx.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gt2pkqnpkyp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gt2gwvhhtbm.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gt2oegfushc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gt2bunuwift.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpqxmrsl.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gt2luuopvfp.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gt2xqellvyn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agvzlluo.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gt2kermpcae.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2zrcgrycf.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gt2tdeproqx.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gt2pnpswcif.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2gidmsdiy.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhfdmwkn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2rpkoiulz.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2eyimgxtt.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gt2hddptkdz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwoqoejz.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2eqkrpzae.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gt2folumfvu.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbbkqoub.html


<!-- 参考信息 -->