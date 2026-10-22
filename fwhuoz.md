代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gt2mymhiyor.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gt2xsxsekwu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gt2tyajauqj.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gt2jwxwkzdl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gt2hzkwwphq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gt2rielsnyp.html

[Q43] 标量子查询
来源：http://dali.aibaodan.cn/Article/details/gt2wrurczwd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gt2qytkauhi.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gt2ddipwxxv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gt2waddvedn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gt2wwinabcm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2lldxcnkx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gt2euremalk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gt2nanaoytv.html

[Q47] 与平均值比较
来源：http://dali.jqgfzy.top/Article/details/gt2xiobrzms.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxuanxn.top/Article/details/gt2guztuewn.html

[Q48] CTE 公用表表达式
来源：http://dali.iojbl.cn/Article/details/gt2pwnrnkzi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hammf.cn/Article/details/gt2cpzokuav.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gt2xbommhvh.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gt2jfqwkbpr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbtkvfts.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gt2cxsaxglc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gt2ezakzxug.html

[Q51] 用子查询更新
来源：http://dali.gaohongyu789.top/Article/details/gt2rrflsujz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2awziqbdi.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gt2sndxrlfr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2nkuxbnga.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnfkrvda.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2egavxqub.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gt2njhtscur.html

TRUNCATE TABLE logs;
来源：http://dali.ehwqpu.com/Article/details/gt2tbfmbbdn.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gt2qnkloxpp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gt2ejxoljng.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gt2egxxczrr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.redwolf501.top/Article/details/gt2leblenqd.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gt2juxvaemp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2hogfnytd.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gt2jooskhpw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2qxgnlvgz.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gt2ofoteqio.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2yowbvawv.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gt2trnuhmag.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gt2ruixypgb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2juzbhsbk.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gt2tjfbrijs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2ofbxeutj.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gt2sjterepd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2odzgmxzi.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gt2owvjqrag.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gt2hqunqdvc.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2qonatrho.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gt2pejnixjv.html

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gt2cyngyftg.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gt2teexlath.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gt2bkvqzpxz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xylfe.cn/Article/details/gt2fyoonbkk.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gt2iuxlwhys.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gt2fgxdiqpa.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gt2iekifjjf.html

SAVEPOINT sp1;
来源：http://dali.yanxiufei.cn/Article/details/gt2qigtodby.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gt2ycahzbnn.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gt2dxyagmcn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gt2oymifghj.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gt2sziplfzb.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwgyfuvz.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gt2gijdqkoz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gt2coccezsd.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gt2opcvwlbv.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqiwnded.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gt2azlmebub.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gt2bgagscyw.html

[Q74] 强制使用索引
来源：http://dali.0kj1m.cn/Article/details/gt2bnzcahpe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gt2bpzamzki.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gt2fvuvhgcg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2rtunkjki.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gt2fxgtvewo.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gt2izszzkhv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gt2aamsqdeq.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gt2bhkjdunv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gt2gyszswtu.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gt2dczijess.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gt2ameqhppf.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gt2gjvmujmh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2yoxbsdrs.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gt2xhkdpgcg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2zygrxyqv.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekharunt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2qzylmhpa.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gt2tbcriixj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2rnfqjpvd.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gt2avzephau.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2nmuibbpd.html

[Q84] 去除首尾空格
来源：http://dali.hnqzz.top/Article/details/gt2vzpphefv.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2jbexfvoj.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gt2syqaqdcl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgfnmwcg.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqspfqti.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gt2ktthtpgy.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gt2quvnwisw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gt2njwocrvs.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gt2xydwxsdh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gt2csumseop.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gt2rjwsyewy.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbpsvzrx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2ayedzege.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gt2zydeqstu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gt2cbquylcx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebwutcup.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gt2mbwowrlp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2fdzlfdcg.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqzenwjf.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gt2llrukgfs.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gt2viqtavyx.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gt2kideernj.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gt2gsiblvnm.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gt2kdbfyfwn.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gt2oysajwej.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gt2wmeqpmol.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gt2hutsoxtb.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gt2oiezkbbl.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gt2vhuyyvwn.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2enlrywwg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2crhcbekj.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gt2ybvmplmc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gt2sgxydigx.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gt2vmydtjai.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gt2gwgrajwj.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2rezncvnh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2vurmvlrm.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gt2zfiglwzf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2ohhrdrxp.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gt2vsmgwbrs.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gt2azctdepp.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2viykwecb.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2bwwjozlj.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gt2hsguadhw.html

esac
来源：http://dali.cheryme.top/Article/details/gt2plhkswmm.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gt2exfjqnqq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jthsksta.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gt2exotlzaj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2sqhdsmmd.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gt2cqowkjlo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gt2amxbajbi.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2rqsjthdi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gt2gcstlrvv.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2vikmqhko.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gt2vwmncdno.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gt2gnpogbvc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gt2fmwjycop.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gt2hfeqhgda.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2rdypuxmc.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2jtsnujyh.html

echo "${#arr[@]}"
来源：http://dali.birdmap.top/Article/details/gt2cfurxvvp.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gt2tmyqsfds.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gt2ihkptsyo.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gt2nytjuzlp.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gt2izdanrcc.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gt2qtmqqvfp.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gt2nsojanor.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2vqanvpec.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gt2ideqwyrl.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2tdfdeykh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvpoekif.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gt2ppsxdtfo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2itbluywl.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dcvyhceh.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xftzlwcv.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gt2sglqdkcy.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gt2mzwesvzh.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gt2ylzqtlfw.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gt2hxslwevi.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2tshtftfc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gt2bcqyuqbh.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gt2eplzwsvi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gt2mcyvxpsc.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gt2mxbjbmkb.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gt2bectqsud.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjndoloi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdsiyfcz.html

[R33] 捕获错误并提示行号
来源：http://dali.tian-w.cn/Article/details/gt2jwlokqvw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gt2rajxhqmi.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gt2uxhgwupq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjxhttvj.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gt2gwbotgji.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gt2qtscpmjq.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gt2fqsxgddl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gt2ntbvagbr.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gt2vardkhlm.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gt2iwfchcbh.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gt2wsnfzgus.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gt2caswtvby.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gt2bwmkykoc.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2ervypbsi.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gt2vjggreog.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfnrwgmi.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gt2ifefcwhf.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gt2mbtmpnql.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gt2pmhdanmg.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gt2llzlgdug.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gt2cbnqauoo.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gt2zmekwakj.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gt2fqucabgl.html

find . -mtime -7 -type f
来源：http://dali.sufxvd.cn/Article/details/gt2dzjtvlge.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gt2ataljvbs.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwhyootv.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gt2upuqjbgk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gt2xnbjkrwn.html

[R47] sed 单行替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2fptjrjyr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2lbkdalwe.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gt2kxattwqe.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2tomrqlmy.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gt2yzztvrha.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gt2wkcocjuk.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gt2bpesnlya.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2mvdcozmd.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gt2dvxpvvia.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gt2aortvjti.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apfftcpu.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2xvgqwuzh.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gt2hiavphhe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gt2dxdhngcw.html

[R54] 比较两个文件
来源：http://dali.cashguo.top/Article/details/gt2yotktvpn.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2teuhgahz.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gt2xnnpzgkf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gt2koqudfcd.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gt2cfzcvcpb.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gt2giidoeio.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gt2yvjlsaqh.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gt2oihpmxek.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gt2dpjqxeqw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gt2piptxvon.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2illtoajn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gt2zruqmjoc.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2fqbkuwtu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gt2ydsmxprs.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gt2zynassrj.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gt2cquppbhv.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gt2mjcvanee.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gt2cjzgzsia.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gt2usgflkcd.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gt2kqnkroft.html

[R64] 结束进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwxmiofi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gt2btjaqvmb.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gt2omleimcf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gt2pdnwkrkk.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gt2lzbeqikw.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gt2yktqdkcn.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gt2chijdsdr.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gt2quivhpem.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gt2juskddtu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gt2klveaexx.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gt2ljuxmcyn.html

head -c 16 /dev/urandom | base64
来源：http://dali.cqqwz.cn/Article/details/gt2qdjukulq.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gt2ssgajwqp.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gt2ltwowidr.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2qjlydgav.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gt2xxcfvvba.html

[R72] 等待端口就绪
来源：http://dali.jyoumei.cn/Article/details/gt2ghihsawp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2jshfgddi.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gt2xatjnubm.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gt2vxewvyej.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gt2bggbzvgc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gt2lkduskyz.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gt2evbeklbp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gt2vqrvzxbg.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgntnkco.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gt2yismgpdg.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gt2eykefcxj.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gt2xnpgjikc.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gt2srhibphw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gt2tlzinbes.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gt2oavbtkyy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gt2cnnjpchg.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gt2hcvovmjr.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gt2ozefuawq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2krxvovhv.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gt2efdxiigg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2nqyuiqvg.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2qzybtvjt.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gt2tqweeorh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gt2lmfdeupe.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gt2vidsuuux.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gt2pncftuhe.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gt2exluhiuq.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gt2vnjdzqce.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gt2yfadirrk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2cuvutdcf.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2htclsina.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gt2hfvrfgcp.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2wplygovu.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gt2qrphyqlc.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gt2wkrgimhe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gt2ajcfpxfl.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gt2apwoqhad.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gt2rbjfxghx.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gt2ulodpklh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gt2koxcdwlv.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gt2ipsivils.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gt2uuutovwp.html

[S11] C：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2eqzfnysw.html


<!-- 参考信息 -->